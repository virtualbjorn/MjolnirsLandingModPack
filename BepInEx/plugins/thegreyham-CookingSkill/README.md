# Valheim.CookingSkill


## Your Cooking Skill will increase when you cook food from either:
- Cooking Station
- Cauldron
- Fermenter

## Buffs Granted:
- Food Health Buff based on Cooking Level. (Default .5% p/level)
- Food Stamina Buff based on Cooking Level. (Default .5% p/level)
- Food Duration Buff based on Cooking Level. (Default 1% p/level)
- Fermenter Duration Reduction based on Cooking Level. (Default .66% p/level)
- Fermenter Drops Increased based on Cooking Level. (Default 1 extra drop at levels 50,75,100)
- Cooking Station Duration Reduced based on Cooking Level. (Default .5% p/level)
- Cooking Station will no longer burn food (Create coal) at specific level (Default lv75)

## How xp is Gained:

- Cooking Station Grants 1 xp by default
- 1/4 of Cooking Station xp is granted when you add an item to the cooking station
- 3/4 of Cooking Station xp is granted when you have successfully cooked the item
- No xp is awarded when you create charcoal.
- Cauldron Grants 2 xp by default
- Fermenter grants 3 xp when you add an item to the fermenter
- Fermenter grants 3xp when you remove a fermented item as the fermenter takes a long time to ferment.
- xp amounts can be configured in the config.


## Buff Examples:
|  | Level 0 | Level 20 | Level 100 |
| ------ | ------ |------ |------ |
| Food Health | 20 | 22 | 30 |
| Food Stamina | 30 | 33 | 45 |
| Food Duration | 300 | 360 | 600 |
| Fermetner Duration | 2400 | 2084 | 815 |
| Fermenter Drops | 6 | 6 | 9 |
| Cooking Station Duration | 60 | 54 | 30 |


## Installation
Ensure you have pipakin's SkillInjector Mod https://www.nexusmods.com/valheim/mods/341 as this utilizes that.
Download via Vortex or extract .dll file and assets folder to BepInEx/plugins 

## Configuration
XP gains and Food buffs can be adjusted in the config file.
To disable the buffs set the relevant Food Effects Multiplier to 0.
