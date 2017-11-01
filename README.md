# External Website of StuStaNet e.V.

## Board
Data in `data/Vorstand.toml`,

## Statue
`stustanet.de/satzung.pdf` is separately configured in Nginx to reverse-proxy (and cache) `https://dokumente.stusta.de/satzung/aktuell/satzung.pdf`, since this URL is not accessible outside of StuSta.
