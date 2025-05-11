# Millénaire-[NAME NOT FOUND ALREADY]
**Millénaire add-on that tweaks and eventually fixes some Millénaire incompatibilities with mods.**

It's been years I play Millénaire and I came across some problems that I fixed in a way or another.
This is not a new custom culture, it modifies existing ones. I will maybe support modded ones but my priority is norman culture for the moment. It takes so much times that I prefer to share my knowledge and let others do their own customizations because millénaire is customizable in a way that you don't need to actually code anything. You don't need to know Java, you just need some english basics and how to edit text files.

This add-on is focused on custom controlled villages, the ones that you can build yourself but I will maybe fix some aesthetic issues with existing buildings like dirt under the "controlled townhall" building


# Introduction
I discovered a lot of things about how Millénaire cultures customization works and found that we can make this mod even more interesting.

What I do here will eventually get documented in https://github.com/G1ll0u/Millenaire-documentation


## What will this add-on do ?


### new custom buildings
It will allow player to create more custom buildings like bigger farms, more guards houses, playgrounds for children etc.
Currently added :
* playgroud (places where children go to play)
* fisherman for normans
* Smaller guard house (less space required)
* Four guards house (arsenal)
* Smaller watchtower (less space required

### millagers improvements
Millagers will be more alive, they won't wait anymore for hours in townhall without doing anything. I achieved that by tweaking millagers goals and adding some aesthetic custom buildings.
* children play on playgrounds
* wifes supervize children while they play
* 

### mods compatibility
Some mods generate things in the world like custom trees (dynamic trees) or custom blocks (like rocks spawning on ground with PVJ). These blocks can sometimes be recognized as "dangerous" by Millénaire and prevents to build anything on it, so it can make villages impossible to find the place to spawn and simply prevent the player from placing a building on it.

My add-on seems to actually fix that !

#### Actually applies for :
* Support for DynamicTrees* (I recommend to use DramaticTrees updated fork)
* Biomes O' Plenty
* Project: Vibrant Journeys
* Forestry

### Eventual performance improvements
I noticed that wifes creates a big workload on the server and I know which goal does that but this goal is essential to the village. I'm working on it because optimizing this goal (make it happen less) can make a huge performance gain.

# Roadmap

**Highest priority**
* Fix millagers sometimes not marrying because of children having all the same family name (requires FTBUtils)
* Add fisherman to normans 
* Fix some modded blocks preventing placing buildings (considered as dangerous so they won't build)
* Allow larger custom buildings (like farms)
* A workaround for the broken custom controlled grove
* Fix patrols
* make wifes craft less pathes

**Medium priority**
* Custom goals that makes villagers and children even more alive
  * make children play at specific places (with a new custom building name playground)
* Allow smaller/bigger custom buildings (like smaller guard houses, lonely guard house, four guards house)

**Lower priority/unsure :**
* polish generated buildings
  * Replace dirt with a better looking block for some norman townhalls
* tweak some goals for TPS performance

**unrelated to this project**
* Make 32x textures for villages that marry good with Conquest_ resource pack
* Create a full bandit cultur

# Fixes progress
| Task      | progress      |
| ------------- | ------------- |
| Workaround for millagers marriage |  found ! |
| Workaround for patrols |  found ! |
| Modded blocks compatibility |  done for the mods listed |
| goals tweaking for TPS | not tested |
| custom controlled grove | task not started |

# New features progress
| Task      | progress      |
| ------------- | ------------- |
| New custom goals | On going, already working
| New custom buildings | On going, already working
| Add fisherman to normans | done but the fisherman is nude (will be fixed)
| balance path blocks spamming in townhall |
## Knowledge requirements
### What should I know ?
* Know how Millénaire works (my documentation could help with that but still WIP : https://github.com/G1ll0u/Millenaire-fixes/)
* Manipulating files and know what is a directory lol (and things like copy-paste)

## Required mods
* WorldEdit (for bigger custom controlled farms)
* FTBUtils for the nbtedit command (To fix millagers not moving in new houses)

## Recommended mods :

* Performance mods listed here (updated list)
* Tiquality (for server side lag, will be explained on documentation)

