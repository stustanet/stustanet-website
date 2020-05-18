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
