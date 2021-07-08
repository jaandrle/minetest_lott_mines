# Minetest mod “LOTT Mines”
- this mod adds abandoned mines, similar to MC. 
- originaly **Mines** by *BlockMen* from [[Mod] Mines [0.3 beta] [mines] - Minetest Forums](https://forum.minetest.net/viewtopic.php?t=6307)
- optimized for usage inside [Lord of the Test - ContentDB](https://content.minetest.net/packages/Amaz/lordofthetest/)
  - hot-fix for non-spawned fences (replace all by trees) → maybe final decision (I like it)
  - increased num of spawning and chests (includig more highter chance for items inside: ingots, mese crystals, …

## Instalation
Move files inside `minetest_config_folder/mods/mines` or `minetest_config_folder/games/lordofthetest/mods/mines` (autoloaded with LOTT game).

## Settings
```
mines_deep_min = -64
^ at this deep mines are created
mines_deep_max = -380
^ up to this deep mines are created
mines_spawnfactor = 1.5
^ increase this value to generate more mines
