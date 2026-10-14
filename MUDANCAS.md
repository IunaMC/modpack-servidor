# Changelog — v2.4.5, Server Performance Improvements and Modpack Maintenance

## Add
- Add [Building Gadgets 2](https://www.curseforge.com/projects/298187) as a building utility expansion, providing additional construction and automation tools for players
- Add [Petting](https://modrinth.com/mod/vf91JXwf) to improve interaction with passive and tameable mobs
- Add [MixinTrace reloaded [NEOFORGE]](https://modrinth.com/mod/wx2WW8va) as a debugging utility to improve mixin error tracking and crash diagnostics
- Add [FallingTree](https://modrinth.com/mod/Fb4jn8m6) to provide improved tree harvesting mechanics and quality-of-life improvements
- Add [LuckPerms Placeholders](https://luckperms.net/wiki/Placeholders) to provide placeholders correctly

## Removed
- Remove [Tropicraft](https://modrinth.com/mod/Tropicraft) due to additional dimension overhead and unnecessary server resource consumption

- Remove unstable or unnecessary server optimization components:
  - [ServerCore](https://modrinth.com/mod/4WWQxlS)
  - [Saturn](https://modrinth.com/mod/2eT8L4q)
  - [Packet Fixer](https://modrinth.com/mod/1jC2fXq)
  - [Noisium](https://modrinth.com/mod/KuNKN7d)
  - [Krypton FNP](https://modrinth.com/mod/7U8nZ3G)
  - [Immersive Optimization](https://modrinth.com/mod/2Y4P6Qy)
  - [Despawn Tweaks](https://modrinth.com/mod/5wYqV5G)
  - [Ksyxis](https://modrinth.com/mod/2jG3f8K)
  - [Clumps](https://modrinth.com/mod/WnN7k7F)
  - [AI Improvements](https://modrinth.com/mod/g5eVx3T)

- Remove [FTB Chunks](https://modrinth.com/mod/9p4J6Lr), [FTB Library](https://modrinth.com/mod/Ol4nF9A) and [FTB Teams](https://modrinth.com/mod/I5G5yR5) from the modpack structure due to removal of their related server functionality

- Remove duplicate or conflicting dependencies:
  - Remove duplicate [SuperMartijn642's Config Lib](https://modrinth.com/mod/LN9BxQ7) dependency as it was already provided by required mods
  - Remove duplicate [MezzConfig](https://modrinth.com/mod/4Gv6vYB) versions to prevent dependency conflicts

## Updated
- Update modpack version metadata from the previous release to `v2.4.5`
- Update the mod list organization and structure to reflect the current modpack composition
- Replace [MixAuth](https://modrinth.com/mod/GzSiVPHb) with [Easy Authentication Mod](https://modrinth.com/mod/aZj58GfX) as the current authentication solution
- Migrate [Player Animation Lib](https://modrinth.com/mod/zjZ3a6k) to the NeoForge version for improved loader compatibility
- Add compatibility support through [Fabric API](https://modrinth.com/mod/P7dR8mSH) and related Fabric ecosystem components required by connected mods
- Update server-side configuration and dependency structure after removing unused optimization and management systems

## MISC
- Reorganize the mod list entries to improve readability and maintain consistency between categories:
  - Required mods
  - Optional mods
  - Server-only mods

- Cleanup obsolete optimization mods that were no longer required or could introduce compatibility issues with the current NeoForge environment
- Improve server stability by reducing unnecessary background systems, integrations and dimension-related overhead
- Improve debugging capabilities by adding [MixinTrace reloaded [NEOFORGE]](https://modrinth.com/mod/wx2WW8va) for better crash investigation
- Synchronize README mod documentation with the current modpack structure
- Prepare version files and metadata for the `v2.4.5` release
- Maintain modpack consistency after authentication changes, dependency cleanup and server optimization adjustments