# External Website of StuStaNet e. V.

## Development

The website generated from the sources in this repository using [Hugo](https://gohugo.io/). To preview the results of your changes, [install Hugo locally](https://gohugo.io/getting-started/installing).

### Repo Structure

The base HTML can be found in `layouts/_default/baseof.html`. All styles are in `static/main.css`.

All content is generated from the markdown files in `content/`.

### Workflow
1. [Fork this repository](https://gitlab.stusta.de/stustanet/stustanet-website/forks/new)
2. Clone your repository locally: `cd` into the parent directory of where the files should be saved, then run `git clone https://gitlab.stusta.de/<your username>/stustanet-website.git` (Or use your favorite Git GUI). Afterwards `cd stustanet-website`.
3. Hugo can generate a live-preview of your changes. Run `hugo -v -w server` in the directory of the cloned repository.
4. Make and commit your changes ([Git tutorial](https://git-scm.com/book/en/v2/Git-Basics-Recording-Changes-to-the-Repository))
5. Push your changes to your fork on Gitlab (`git push`).
6. [Create a merge request](https://gitlab.stusta.de/stustanet/stustanet-website/merge_requests/new)

## Board
Data in `data/Vorstand.toml`,

## PGP Keys
Keys are stored in the `content/keys` folder. Board keys (Vorstandskeys) are stored in files named
`vorstand_2x_2y.md` in the content section. The key itself needs to be put into the `{{< key >}}`
shortcode. Furthermore, the following two front matter variables should be set: `type: "vorstands_key"`
and `title: ".."` should be set to keys name for example "Vorstand 21/22" (this will be shown on the
website!). One can also define `fingerprint: "..."` with the keys fingerprint to allow users to 
compare their given key.

Every board member can also upload his or her public key into the respective file in `content/keys/board`.
The files work similar to the board keys except that the `type` front matter variable should **not**
be set and the `expiryDate` variable **should** be set to the date where the board member will no
longer be in office. This will tell hugo to no longer include the key when creating the static webpage.

### PGP Cheat Sheet
```bash
# generate key
gpg --gen-key
# list all keys
gpg --list-keys
# export key in ascii format, e.g. key CB63071990D6ED1213015E5E32E91A27940020FF
gpg -a --export CB63071990D6ED1213015E5E32E91A27940020FF
# or export to file
# (email addresses can also be used to identify keys)
gpg -o board.key -a --export vorstand@stustanet.de
# show fingerprint
gpg --fingerprint vorstand@stustanet.de
```
For further reference see https://www.gnupg.org/gph/de/manual/r1023.html or `man gpg` :)