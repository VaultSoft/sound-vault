# FatherOfDraven Sound Vault

Free League of Legends per-champion voice lines, sound effects and ambient tracks,
pulled from game files and organized by champion.

**Browse & download:** https://vaultsoft.github.io/sound-vault/

## How it works
- Audio lives under `downloads/` (organized by category then champion).
- On each push, the `zip-packs` workflow builds one zip per champion and publishes
  them to the `sound-packs` release.
- The landing page (`index.html`) links to those release assets.
- `downloads/` is excluded from the Pages build (`_config.yml`) so the site stays small.

Not affiliated with or endorsed by Riot Games.
