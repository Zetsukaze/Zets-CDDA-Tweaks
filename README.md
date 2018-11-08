# Zetsukaze's CDDA Tweaks!
Minor tweaks to make the game more to my liking, some of the changes are OP, but this is a play your way game!

# Usage Guide
1. Unzip the downloaded file and copy the mod folder into `<CDDAInstallationFolder>\data\mods`
2. For mods that you do not play with, remove the dependency from [modinfo.json](modinfo.json)
3. Remove the related files of the disabled mods
4. Enable in CDDA `Zetsukaze's CDDA Tweaks` and enjoy the variety of hairs, eyes and skins!

For example, if you do not play with [Cataclysm++](https://github.com/Noctifer-de-Mortem/nocts_cata_mod), then remove `Cata++` from [modinfo.json](modinfo.json) and the `cata++` JSON files.

# List of Changes
* [Base Game](#base-game)
  * [Tool Armor](#tool-armor)
  * [Vehicle Parts](#vehicle-parts)
* [Blazemod aka Vehicle Additions Pack](#blazemod)
  * [Vehicle Parts](#vehicle-parts-1)
* [Cataclysm++](#cataclysm)
  * [Armor](#armor)
  * [Vehicle Parts](#vehicle-parts-2)
* [Shardstuff](#shardstuff)
  * [Vehicle Parts](#vehicle-parts-3)

## Base Game
### Tool Armor
##### Survivor Utility Belt
This is a survivor's utility belt, why wouldn't a survivor add belt loops to keep tools, as well as larger knives?
* Added the ability to holster tools
* Added the ability to keep up to 3 items
* Changed the storage volume `Min: 0L - Max: 3L`

### Vehicle Parts
##### Minifreezer
Yeah yeah, mini I know, but come on, I have stacks of meat I need to freeze!
* Increased the storage volume to `350L` (Same as DC Fridge from Cata++)
* Added the `LOCKABLE_CARGO` flag

##### Minifridge
* Added the `LOCKABLE_CARGO` flag

##### Internal Boom Crane
* Added the `FOLDABLE` flag

## Blazemod
### Vehicle Parts
##### Cargo dimensions!!!
I added the ability to install cargo lock sets, because who wants those grubby NPC paws on your sweet loot? Also, fold it up and carry around your own pocket dimension!
* Added the `LOCKABLE_CARGO` flag
* Added the `FOLDABLE` flag
* Temporarily changed the storage volume to 10,000L, will remove once [this](https://github.com/CleverRaven/Cataclysm-DDA/pull/26493) is approved.

## Cataclysm++
### Armor
##### Survivor's Archer Backpack
A backpack and a quiver all rolled into one! Of course I want to carry more loot :smirk:
* Increased the storage volume to `25L`
* Decreased the warmth to 0. Who wants a sweaty back?

##### Survivor's Scout Suit & Survivor's Armored Scout Suit
* Decreased the warmth to 25. Way too much warmth on these things.

### Vehicle Parts
##### DC Fridge
* Added the `LOCKABLE_CARGO` flag

##### Survivor's Station
* Added the `LOCKABLE_CARGO` flag

## Shardstuff
### Vehicle Parts
##### 100L & 200L Internal Tanks
* Added the `looks_like` flag to make it use the same tile as the external tanks

# My CDDA Mods
[Zetsukaze's Hair Extensions](https://github.com/Zetsukaze/Zets-Hair-Extensions)

[Zetsukaze's CDDA Tweaks](https://github.com/Zetsukaze/Zets-CDDA-Tweaks)
