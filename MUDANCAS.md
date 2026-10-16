# Changelog — v2.14.0, Botany Pots, Power Scale and Semantic Versioning

## Add
- Add [Botany Pots](https://modrinth.com/mod/U6BUTZ7K) to grow crops in compact pots, ideal for automated farms
- Add [Botany Trees](https://modrinth.com/mod/mvs7RoIW) to grow trees in Botany Pots
- Add [Power Scale](https://modrinth.com/mod/wkeZjUcx) to let players scale down their own stats (speed, damage and other attributes) in 5 steps
- Add dependency [Silent Lib](https://modrinth.com/mod/silent-lib) `10.6.0`

## Updated
- Move dependencies [Bookshelf](https://modrinth.com/mod/bookshelf-lib) `21.1.81` and [Prickle](https://modrinth.com/mod/prickle) `21.1.11` from optional to required, since they are now needed by required mods
- Release workflow now builds the package from `index.lock` and downloads Git LFS files before packaging
- Adopt Semantic Versioning: adding, removing or updating mods bumps the minor version
