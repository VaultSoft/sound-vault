# FatherOfDraven Sound Vault

League of Legends champion and skin audio for creators — a mix of gameplay
recordings and game files, shared free to use, organized by champion.

**Browse & download:** https://vaultsoft.github.io/sound-vault/

## How it works
- Audio lives under `downloads/` (organized by category then champion).
- On each push, the `zip-packs` workflow builds one zip per champion and publishes
  them to the `sound-packs` release.
- The landing page (`index.html`) links to those release assets.
- `downloads/` is excluded from the Pages build (`_config.yml`) so the site stays small.

League of Legends and its characters, sounds and other game assets are owned by
Riot Games and/or their respective rights holders. FatherOfDraven Sound Vault is
an independent fan project and is not affiliated with or endorsed by Riot Games.
