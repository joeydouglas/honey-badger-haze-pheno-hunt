# Honey Badger Haze Pheno Hunt - Data Repo

Markdown record of truth for the **Honey Badger Haze** pheno hunt
((C99 x White Widow) x Ms. Universe #10, Dynasty Genetics lineage),
ingested from the shared #breeding Discord channel.

## Contents

- `project.md` -- project-level frontmatter and notes
- `plants/<ID>.md` -- one file per plant (`HBH01`, `HBH02`, ...)

Plant IDs are parsed from Discord text via `\bHBH[\s-]?(\d{1,2})\b`.

`breeding-data-api` clones this repo and serves `project.md` and
`plants/<ID>.md`; the frontend renders from that API.

## Legacy dashboard

The generated static dashboard that used to live here (`index.html`,
`style.css`, `plants/*.html`) moved to
[joeydouglas/honey-badger-haze-pheno-hunt-dashboard-legacy](https://github.com/joeydouglas/honey-badger-haze-pheno-hunt-dashboard-legacy).

The `.github/` workflow stays here: it triggers the DigitalOcean redeploy
so the API re-clones after new observations land.
