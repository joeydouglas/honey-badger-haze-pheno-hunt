# Honey Badger Haze Breeding Tracker

Automated breeding-population dashboard for the **Honey Badger Haze** cross ((C99 x White Widow) x Ms. Universe #10, Dynasty Genetics lineage), ingesting live observations from the shared #breeding Discord channel and syncing to Google Drive.

- Live dashboard: https://joeydouglas.github.io/honey-badger-haze-breeding/
- Plant ID convention: `HBH01`, `HBH02`, ... (parsed from Discord text via `\bHBH[\s-]?(\d{1,2})\b`)
- Source of truth: `tracker.json` in the companion `~/.hermes/breeding/honey-badger-haze/` working directory (not this repo -- this repo holds the generated static dashboard only).

## Status

Newly scaffolded (2026-08-29) from the Lantz project template. No plant observations have been logged yet -- `tracker.json`'s `plants` array is empty and the dashboard will populate automatically as observations come in via the #breeding channel.
