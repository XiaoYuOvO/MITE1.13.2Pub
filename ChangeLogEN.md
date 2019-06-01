[中文版](https://github.com/XiaoYuOvO/MITE1.13.2Pub/blob/master/ChangeLogCN.md)
# B0.6.0 ChangeLog
## Game mechanics
* Shorten the block placement distance\
  _(When empty-handed with blocks: 2.75 blocks, empty-handed with entities: 1.5 blocks)_
* Reduce the rate of hungry damage speed
* Block placement speed is reduced by 5tick
* Attack accelerates hunger
* Placing block accelerates hunger
## Anti-cheating
* Lock difficult to hard 
* Brightness setting locks to dark
## Mobs
* Killing animals can't gain experience
---
# B0.5.8 ChangeLog
_**(Due to copyright problems with this mod, I have to stop a version to make these changes.)**_
## Technical
* Encrypt MITE with native library,to make it unable to be decompiled
## GUI
* Add the ID of the author of this mod to the main GUI and credits list
* Add a button to open the Github repository to the main GUI
## Generating
* Change the height of the dungeon in the underworld, with a minimum of 140
## Bug fix
* fix [#34](https://github.com/XiaoYuOvO/MITE1.13.2/issues/34) 
--- 
# B0.5.7 ChangeLog
## Generating
* Add the two bedrock layers and its stone hole in the underworld's underground
## Block
* Add two portals to get to underworld and world spawn point\
 (Going to the underworld needs to build a portal in the overworld where Y is less than 16.)\
 (Going to the nether needs to build a portal in the underworld where Y is less than 16.)
---
# B0.5.5 ChangeLog
## World
* Add a new world--Underworld\
(Now only can into it by using`/execute in minecraft:underworld run tp @s ~ ~ ~`)
## Generating
* Add the generating of all kinds of ores except adamantium
---
# B0.5.3 ChangeLog
## Bug Fix
* Correct the sleep time, let the time after sleeping be sunrise,\
make the sleep not reset the number of days
* Fix the bug that the workbench can't be opened in caves
* Correct the fall damage to make it the same as the vanilla MITE
## Generating
* Reduce the size and range of gravel generating in the world
---
# B0.5.2 ChangeLog
## Blocks
* 1、Add various crafting tables
* 2、Add various furnace
## Items
* Add emerald,diamond,quartz,glass,obsidian and flint's shard
## Item Dropping
* Modify the drop rate of various drops of gravel, as shown in the following table

Drop| Chance
------------ | -------------
Gravel |3/4 
Flint Shard |5/32 
Copper Nugget |1/18 
Silver Nugget |1/54 
Flint |1/96 
Gold Nugget |1/162 
Obsidian Shard |1/486 
Emerald Shard |1/1458 
Diamond Shard |1/4374 
Mithril Nugget |1/13122 
Adamantium |1/26244 
---
# B0.5.0 ChangeLog
## Blocks
* Add all kinds of material anvils
## Game mechanics
* 1,Now we need to unlock structures to make them can spawn in world.The requirements are in \
    the advancement page,you need to get to 10 levels to unlock the root advancement of all structures
* 2,Make enchanted books cannot merge together

## Generating
* The animals in Taiga is fewer now

## Rendering
* 1,Make players always can see the durability of items
* 2,Fix the textures of iron anvils

## Bug Fix
* 1,Fix cannot craft fireworks,color clothes and cloning books
* 2,Fix an issue where multiplayer games could not be played due to packet transfer
* 3,Fix [MC-101233](https://bugs.mojang.com/browse/MC-101233)

## Other
* Removed tutorial step of punching trees
---
# B0.4.0 ChangeLog
## Game mechanics
* Now the item is more easily damaged: \
  The received damage value of tools is 100 times the hardness of the digging block(Axes are 45 times)\
 The received damage value of swords is 50
     
## Item
* 1, Add swords, pickaxes, shovels, axes, hoe of all levels of the vanilla 1.6.4 MITE.
* 2, adding a new material - tungsten, better than Mithril, worse than Adamantium, durability is twice the size of Mithril's

## Blocks
* Add new ores and metal blocks of various materials
---
# B0.3.1 ChangeLog
## Bug Fix
* The health of player is 20 when join world for first time,it should be 6
---
# B0.3.0 ChangeLog
## Game mechanics
* 1, Upgrade requires a higher experience value:\
   Set the level to n\
   Required experience per level = 10 (n + 1)\
   Total experience per level = 5n2+15n
* 2 run, jump and destroy blocks' hunger value plus (X1.5)
* 3, dirt sand leaves slowdown:\
   11s 10.5s 10s
* 4, death drops one-third of the experience before death, if there is no level, it will fall to a negative number

## Generating
* 1, the animal production rate is reduced, generating weights, halving the size of each group
* 2, generate creatures every 128 days

## Item
* Remove wooden pickaxe, wooden axe, wooden hoe

## Bug fix
* Player's health is no real 3 hearts on respawn

## Anti-cheating
* 1, coordinate deletion
* 2, prohibiting the use of cheating
* 3, update the saves file version, now only supports the opening of the MITE saves
---
# B0.2.1 ChangeLog
## Items
* Add flint tools
* Add salad
* Make seeds eatable

## Item drops
* Make flint's drop chance lower
* Make leaves drop sticks

## Game mechanic
* Changed the hunger mechanism to make the game harder

## Block
* Dirt will drop down like gravel and sand

## Technical
* Make the language files can include in the jar file