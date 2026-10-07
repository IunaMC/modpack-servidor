# Changelog — v2.0.0-beta.02, Server Stability Improvements and Modpack Maintenance

## Add
- Add [MixAuth](https://modrinth.com/mod/GzSiVPHb) as the new server authentication solution, replacing the previous authentication system due to server crashes

## Removed
- Remove [Easy Authentication Mod](https://modrinth.com/mod/aZj58GfX) due to server crashes and compatibility issues
- Remove [LuckPerms](https://modrinth.com/mod/Vebnzrzj) and [LuckPerms Placeholders] due to server crashes
- Remove [Wind's Spellbooks : Iron's Spells 'n Spellbooks Addon](https://modrinth.com/mod/nTApwmMc) due to server crashes
- Remove unused or unstable server components:
  - [Easy Authentication Mod](https://modrinth.com/mod/aZj58GfX)
  - [LuckPerms](https://modrinth.com/mod/Vebnzrzj)
  - [Wind's Spellbooks : Iron's Spells 'n Spellbooks Addon](https://modrinth.com/mod/nTApwmMc)

## Updated
- Update modpack version metadata from `v2.0.0-beta.01` to `v2.0.0-beta.02`
- Update the mod list organization and structure in `README.md`
- Move [Just Enough Items](https://www.curseforge.com/minecraft/mc-mods/jei) from optional dependencies to required mods, as it became mandatory for the current modpack setup

## MISC
- Reorganize the mod list entries to improve readability and maintain consistency between categories:
  - Required mods
  - Optional mods
  - Server-only mods

- Cleanup unstable server-side integrations and temporary components causing crashes
- Improve server reliability by replacing problematic authentication and permission-related systems
- Synchronize README mod documentation with the current modpack structure
- Prepare version files and metadata for the `v2.0.0-beta.02` release