[中文版](https://github.com/XiaoYuOvO/MITE1.13.2Pub/blob/master/ChangeLogCN.md)
# B0.8.4 ChangeLog
## Blocks
* Make tips for fuels that cannot be burn in a furnace
## Mobs
* Make llamas,polar bears and wolfs wont attack players when other animals besides them attacked by player
* Make squids will attack players
* Reduce the speed of animals producing manure
## Game mechanism
* Make the IR value bigger to get the IR effect
* Decreased the speed of players being hungry
* Decreased the range of checking mobs around players when players try to sleep
## Bug Fix
* Fix sometimes furnace can smelt items with the incorrect fuels
* Fix glow earth elemental's textures
* Fix flint hatch's handing model
* Fix cannot break chest by hand
* Fix portals cannot get to the correct place
## Others
* Modified the text of cannot sleep
---
# B0.8.3 ChangeLog
## Game mechanism
* Make creative mode players can place block, hit entity and craft item when them haven't food value
* Decreased the value of having insulin response
## Blocks
* Make plants' growth speed similar as the vanilla MITE
* Increased the chance of dropping seed from grass
## Mobs
* Make wight can steal less players' exp 
## Bug Fix
* Fix salad bowl will disappear when eat it with a stack of salad
* Fix tungsten chainmail armors' durability
* Fix `/nutrition` command occur error in server
* Fix player cannot eat food in server
* Fix sometimes animal manure cannot pickup
## Others
* Make player can use password to enter server to prevent others steal their things
## Command
* Players in server can use command `/password reset <old_password> <new_password>` to reset your password
* Server side can use command `/passwoed reload` to reload passwords
---
# B0.8.2 ChangeLog
## Items
* Add manure and animal can make manure
## Blocks
* Make dead bush drop less sticks
* Make leaves drop more sticks
## Mobs
* Make horse drops beef and leather
## Mob spawns
* Make mobs appear more on the first day
## Game mechanism
* Make player cannot place block or attack others or craft item when it has no food level
* Add food insulin response
* Make players' saturation level less when players spawn
* Players only have 80% attack damage when they are in water
## Bug Fix
* Fix crafting table can copy item
## Others
* Make server op can use server commands
* Make the client and server must be the correct version to each other in order to establish a connection
---
# B0.8.1 ChangeLog
## Game mechanism
* Add food nutrition
## Item
* Add nutrition values for all the foods
* Add potion effects for red mushroom
* Make eggs can eat directly,and press CTRL and use to throw out
## Command
* Add command `/nutrition`\
   usage:   `/nutrition (add|set) <target(s)> (phytonutrients|protein) <value>`
## Render
* Make player cannot see advanced item stack info without development mode
## Others
* add recipes for all weapons and tools and armors
* Modified some recipes' crafting tier
* Add color _Orange_(a bit yellower than normal orange),code of it is `g`
* Make server can contain offline players and online players
## Bug Fix
* Fix server console to be able send command
* Fix sometimes falling anvil causes crash
---
# B0.7.7 ChangeLog
## Items
* Add placing source and picking up source describes of bucket
* Make armor's toughness and armor value depends on armor's durability\
(armor value and toughness will be decreased when durability lower than half)
## Game mechanism
* Changed the way of damage calculation\
  The form of damage and armor is listed below *(toughness is 0)*
    
    Armor→ Damage↓ |1.0|2.0|3.0|4.0|5.0|6.0|7.0|8.0|9.0|10.0|11.0|12.0|13.0|14.0|15.0|16.0|17.0|18.0|19.0|20.0|
   ----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|----|
   1.0 | 0.94375 | 0.86875 | 0.79375 | 0.71875 | 0.64374995 | 0.56875 | 0.49374998 | 0.41875 | 0.34375 | 0.26874995 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 
   2.0 | 1.925 | 1.775 | 1.625 | 1.4749999 | 1.325 | 1.175 | 1.025 | 0.875 | 0.7249999 | 0.5749999 | 0.42499995 | 0.27499998 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 
   3.0 | 2.94375 | 2.71875 | 2.49375 | 2.2687502 | 2.0437498 | 1.8187499 | 1.59375 | 1.3687499 | 1.14375 | 0.9187499 | 0.69374996 | 0.46874982 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 
   4.0 | 3.94 | 3.7 | 3.4 | 3.1 | 2.8 | 2.5 | 2.1999998 | 1.8999999 | 1.5999999 | 1.3 | 1.0 | 0.6999998 | 0.39999986 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 
   5.0 | 4.925 | 4.71875 | 4.34375 | 3.96875 | 3.59375 | 3.2187498 | 2.84375 | 2.46875 | 2.09375 | 1.71875 | 1.3437498 | 0.9687498 | 0.5937499 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 
   6.0 | 5.91 | 5.7749996 | 5.325 | 4.875 | 4.4249997 | 3.9750001 | 3.5249999 | 3.0749998 | 2.625 | 2.1749997 | 1.7249998 | 1.2749999 | 0.8249999 | 0.37499964 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 
   7.0 | 6.895 | 6.79 | 6.34375 | 5.81875 | 5.2937503 | 4.7687497 | 4.24375 | 3.71875 | 3.1937497 | 2.6687498 | 2.1437497 | 1.6187499 | 1.0937495 | 0.56874967 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 
   8.0 | 7.88 | 7.76 | 7.4 | 6.8 | 6.2 | 5.6 | 5.0 | 4.3999996 | 3.7999997 | 3.1999998 | 2.6 | 2.0 | 1.3999996 | 0.7999997 | 0.25 | 0.25 | 0.25 | 0.25 | 0.25 | 
   9.0 | 8.865 | 8.7300005 | 8.493751 | 7.81875 | 7.1437497 | 6.46875 | 5.79375 | 5.11875 | 4.44375 | 3.76875 | 3.09375 | 2.4187496 | 1.7437496 | 1.0687498 | 0.3937499 | 0.25 | 0.25 | 0.25 | 0.25 | 
   10.0 | 9.85 | 9.700001 | 9.55 | 8.875 | 8.125 | 7.3749995 | 6.625 | 5.875 | 5.125 | 4.375 | 3.6249995 | 2.8749995 | 2.1249998 | 1.3749999 | 0.6249994 | 0.25 | 0.25 | 0.25 | 0.25 | 
   11.0 | 10.835 | 10.67 | 10.505 | 9.96875 | 9.14375 | 8.31875 | 7.4937496 | 6.66875 | 5.84375 | 5.018749 | 4.1937494 | 3.3687496 | 2.5437498 | 1.7187493 | 0.8937495 | 0.25 | 0.25 | 0.25 | 0.25 | 
   12.0 | 11.82 | 11.64 | 11.46 | 11.1 | 10.200001 | 9.299999 | 8.4 | 7.5 | 6.5999994 | 5.7 | 4.7999997 | 3.8999999 | 3.0 | 2.0999994 | 1.1999996 | 0.2999997 | 0.25 | 0.25 | 0.25 | 
   13.0 | 12.805 | 12.610001 | 12.415 | 12.22 | 11.29375 | 10.318749 | 9.34375 | 8.36875 | 7.39375 | 6.41875 | 5.44375 | 4.46875 | 3.4937494 | 2.5187495 | 1.5437497 | 0.56874985 | 0.25 | 0.25 | 0.25 | 
   14.0 | 13.79 | 13.58 | 13.37 | 13.16 | 12.425 | 11.375 | 10.324999 | 9.275001 | 8.224999 | 7.1749997 | 6.125 | 5.0749993 | 4.0249996 | 2.9749997 | 1.9249998 | 0.87499917 | 0.25 | 0.25 | 0.25 | 
   15.0 | 14.775001 | 14.55 | 14.325 | 14.1 | 13.59375 | 12.46875 | 11.34375 | 10.21875 | 9.09375 | 7.96875 | 6.843749 | 5.7187495 | 4.5937495 | 3.4687498 | 2.343749 | 1.2187493 | 0.25 | 0.25 | 0.25 | 
   16.0 | 15.76 | 15.52 | 15.28 | 15.04 | 14.8 | 13.6 | 12.4 | 11.2 | 10.0 | 8.799999 | 7.5999994 | 6.3999996 | 5.2 | 4.0 | 2.7999992 | 1.5999994 | 0.39999962 | 0.25 | 0.25 | 
   17.0 | 16.745 | 16.49 | 16.235 | 15.98 | 15.725 | 14.768749 | 13.49375 | 12.21875 | 10.943749 | 9.668751 | 8.393749 | 7.1187496 | 5.84375 | 4.5687494 | 3.2937493 | 2.0187497 | 0.7437498 | 0.25 | 0.25 | 
   18.0 | 17.73 | 17.460001 | 17.19 | 16.92 | 16.65 | 15.974999 | 14.625 | 13.275 | 11.925 | 10.575 | 9.224999 | 7.875 | 6.524999 | 5.174999 | 3.8249996 | 2.475 | 1.1249989 | 0.25 | 0.25 | 
   19.0 | 18.715 | 18.43 | 18.145 | 17.86 | 17.575 | 17.21875 | 15.79375 | 14.368751 | 12.943749 | 11.51875 | 10.09375 | 8.668749 | 7.243749 | 5.8187494 | 4.3937497 | 2.9687488 | 1.5437491 | 0.25 | 0.25 | 
   20.0 | 19.7 | 19.400002 | 19.1 | 18.8 | 18.5 | 18.199999 | 17.0 | 15.5 | 14.0 | 12.5 | 10.999999 | 9.499999 | 7.9999995 | 6.5 | 5.0 | 3.499999 | 1.9999993 | 0.49999952 | 0.25 | 
---
# B0.7.6 ChangeLog
## Items
* Make bucket cannot put the water source unless press "ctrl" key and pay 100xp for it
* Now you need to use an empty bucket and press "ctrl" key to pick up a fluid source
* Bucket can pickup flowing fluid
* Add all kinds of metal buckets
* Buckets might be smelted when pick up lava(the chance of smelt can be seen when you hover your mouse to a empty bucket and press "shift" key)
## Bug Fix
* Fix some vanilla bug:\
    [MC-100946](https://bugs.mojang.com/browse/MC-100946)\
    [MC-103313](https://bugs.mojang.com/browse/MC-103313)
---
# B0.7.5 ChangeLog
## Items
* Add all kinds of metal fishing rods
---
# B0.7.4 ChangeLog
## Items
* Add all kinds of arrows
* Add ancient metal bow and mithril bow
## Entity
* Changed longdead's bow and arrow to ancient metal bow and ancient metal arrow
## Bug Fix
* Fix that ancient bone lord's armor change to ancient metal chainmail's after summoning longdead
---
# B0.7.3 ChangeLog
## Items
* Add quality for all weapon and armors
## Rendering
* Now the crafting GUI will show the tip text for players when player cannot craft item
## Command
* Now you can use `/xp query total` to query your total experience
## Bug Fix
* Fix some bugs of crafting
---
# B0.7.2 ChangeLog
## Items
* Fix shears' name
* Add all kinds of metal shields
* Make shields cannot defense all damages and knockback
* Make shields have cooldown
* Make shield won't take up too much space on the screen
#### The properties of shields are shown below

Material|Durability|Cooldown(Sec)|Damage Reduction| Knockback Resistance
--------|----------|-------------|-----------------|---------------------
Copper   | 32      |7            | 20%             | 30% 
Silver   | 32      |7            | 20%             | 30% 
Rusted Iron   | 16      |7.5            | 10%             | 20% 
Iron   | 64      |6            | 30%             | 40% 
Gold   | 48      |6.5            | 25%             | 35% 
Ancient Metal   | 128      |5            | 40%             | 50% 
Mithril   | 256     |4            | 50%             | 60% 
Tungsten   | 512     |3            | 60%             | 70% 
Adamantium   | 1024     |2            | 70%             | 80% 
  

---
# B0.7.1 ChangeLog
## Items
* Add all kinds of metal tools and metal weapons
* Make shears can collect leaves,lily pad,vine and web
* Add reach bounce for all tools
## Bug Fix
* Fix the number of days displayed in debug screen
---
# B0.7.0 ChangeLog
## Items
* Remove diamond armors
* Add all kinds of metal armors
## Generating
* Add spawn condition for stronghold, igloo and swamp hut
## Blocks
* Tweak some blocks' hardness
## Entities&Mobs
* Decrease skeleton's ranged attack speed again...
* Increase skeleton's melee attack's movement speed
* Make arrow in ground disappear faster
* Fix fire element's spawning
---
# B0.6.11 ChangeLog
## Block
* Adjust the hardness of blocks to adjust the durability of the tool
## Item
* Make bonemeal cannot make plants grow faster
* Change the method of item's attack damage calculation and damage to make them consistent with the vanilla MITE
* Add sword's reach bounce(now it's 1.25 block)
## Mobs
* Decrease skeleton's ranged attack speed and its arrow's hitbox
* Add armors for Ancient Bone Lord
* Make ghoul's attack can give player 2 sec's slowness and change player's head rotation
* Make invisible stalker can not pickup loot
* Decrease the time it takes for shadow attack to cause blindness(now it's 7 sec)
* Change some mobs' max health
## Bug Fix
* Fix the damon spider's attack make player in fire for too long time
* Fix killing witch cannot remove curse
## Generating
* Add spawn for all new mobs
* Remove natural spawning of witch
* Decrease the count of natural spawning ores
* Add underworld mycelium
* Add underworld bone lord spawner dungeon
---
# B0.6.10 ChangeLog
## Mobs
* Now witch will curse players when it spawn,you need to kill the witch who cursed you to remove the curse\
  The curses which the witch can use to players are:
  
  Name| Description
  ------------ | -------------
   Corrosive skin  | The equipments you are using will drop 2 durability each sec
   Cannot hold breath  | You cannot stay in water for long time
   Cannot run  | You cannot run
   Cannot eat meat  | You cannot eat any meat
   Cannot eat vegetable  | You cannot eat any vegetable including any plant products
   Cannot drink  | You cannot drink soup or eat stew
   Ender hatred  | Enderman will attack you at any time
   Intellectual decline  | Your crafting speed will be slower(The crafting time is two times of normal)
   Fear plant  | You will be slow when you crossing plants
   Armor exclusion  | You cannot wear armors
   Fear chest  | You cannot open any chests
   Cannot sleep  | You cannot use the bed
   Fear spider  | You can hardly attack spider
   Fear wolf  | You can hardly attack wolf
   Fear creeper  | You can hardly attack creeper
   Fear undead  | You can hardly attack undead mobs
## Command
* In developer mode, you can use the `/curse [curse name] [player]` command to set the curse of yourself and others (none is no curse)
---
# B0.6.9 ChangeLog
## Effects
* Added _**suffocation**_ effect, which will cause the player to continuously decrease the air value. \
  The higher the level, the faster the air value drops.
## Mobs
* Drowned is faster in water or rainy day,but it is slow in daylight,and it will give player **_suffocation_** effect
* Vindicator can disarm players when it attacks(10 sec cooldown)
* Added Vindicator guardian(run faster and causes more damage)
---
# B0.6.8 ChangeLog
## Mobs
* Add Black widow spider,demon spider,wood spider,shadow and dire wolf
* Slow down the running speed of panic animals
* Increase phase spider's attack dodging chance
## Bug Fix
* Fix various slime names so that they correctly display the current variant
* Fix a bug where the throwing Slim ball did not match the item.
---
# B0.6.7 ChangeLog
## Items
* Add ancient metal armors and rusted iron armors
## Effects
* Make **_slowness_** effect can slow down camera move speed 
## Mobs
* Add bone lord,ancient bone lord and netherspawn silverfish,copper spine silverfish,hoary silverfish and invisible stalker
* Change skeletons' max health
* Now squids will give players slowness debuff
* Add armors for revenant and longdead
* Mobs attack range will be affect by holding items
---
# B0.6.6 ChangeLog
## Mobs
* Added a variety of slime
* Let slime can corrode blocks and equipment
## Game mechanism
* Changed the calculation of the hardness of blocks
## Items
* Added a variety of slime balls
* Let the slime ball can be thrown out
## Bug Fix
* Fix attacking turtles causes crash
---
# B0.6.5 ChangeLog
## Rendering
* Add lighting eyes for many mobs(longdead,vampire bat,nightwing,phase spider and revenant)
## Mobs
* Add hellhound, fire elemental and infernal creeper
* Make Zombie Pigman attack players when they meet
## Blocks
* Logs broken by explosion now only drop sticks
## Bug Fix
* Fix guardian longdeads' weapons for their first spawn and their attacking animation
---
# B0.6.4 ChangeLog
## Mobs
* Add Revenant and Longdead
* Add Vampire Bat,Giant Vampire Bat and Nightwing
## Items
* Add Rusted Iron tools
## Bug Fix
* Fix that lag when player with a lot of exps died 
---
# B0.6.3 ChangeLog
## Mobs
* Add Ghoul, Earth Element, Phase Spider, and Wight
* Increase range of help for others for mobs
* Increase the hitbox of arrows shot by skeleton to make it easier to hit
---
# B0.6.2 ChangeLog
## Mobs
* Increase mobs' follow range
* Zombie and Skeleton will have wooden club or wooden shovel when spawn
* Make cow can produce only one bucket of milk once a day
* Make arrow can cross leaves and hurt entities
* Make animals will run away when others or itself hurt by entity
## Bug Fix
* Fix that crash when projectile hit entities
* Fix that player has 20 food levels when world generated
## Generating
* Decrease the counts of copper ore and silver ore per chunk
## Items
* Change wooden sword to wooden club
---
# B0.6.1 ChangeLog
## Effects
* Add Drowned Effect,it can make players can't swim and be drowned
## Mobs 
* Squids can break boats and make players drowned
* Zombie will attack animals
* Spider can throw web to players to make the players become slowly
* Zombie can dig some soft blocks to get close to players
## Bug Fix
* Fix sword hasn't reach bounce
* Fix hard to put block under player
---
# B0.6.0 ChangeLog
## Mobs
* Killing animals can't gain experience
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