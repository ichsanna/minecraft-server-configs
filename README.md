# Minecraft Server Configs
I use the following server configurations, plugins, and datapacks for my private SMP server. The purpose is to rework boring elements, add new gameplay mechanics, and introduce new exploration feels.

**Please note that the plugins, datapacks, and resource packs below is used on Minecraft 1.20.4 and hasn't been tested on different versions. Some incompatibility may occur if played on a different version.**

## How to Setup
1. Make sure you've installed Java.
2. Clone this repo.
3. Download the Paper and put it on main directory
4. Run Paper using the following command: `java -jar paper-1.20.4-478.jar -nogui`. The filename depends on your Paper version.
5. Before you proceed further, you need to agree to the EULA in "eula.txt".
6. Download the plugins and put them inside "plugins" directory.
7. Create "world" directory then "datapacks" inside "world" directory.
8. Download the datapacks and put them inside "world/datapacks" directory.
9. Download the resource pack and upload it somewhere easy to access via a direct URL.
10. Change "resource_pack" URL in "server.properties" file.
11. Change server map URL in "plugins/CommandPanels/panels/panel-1.yml".
12. Run Paper again.
13. Connect to server using Minecraft Client. Enjoy!

## Server Software
- [Paper](https://papermc.io) - High performance server based on Spigot.
## Plugins
- [Aura Skills](https://www.spigotmc.org/resources/auraskills-formerly-aurelium-skills.81069/) - Adds RPG elements & skills.
- [Command Panels](https://www.spigotmc.org/resources/command-panels-custom-guis.67788/) - Adds GUI based menu to give info & access various commands with only clicking.
- [Chunky](https://www.spigotmc.org/resources/chunky.81534) - Pregenerates chunks so the server will use fewer resources when the players explore new locations.
- [Dynmap](https://www.spigotmc.org/resources/dynmap%C2%AE.274/) - Renders server map which can be viewed from the browser.
- [Excellent Enchants](https://www.spigotmc.org/resources/excellentenchants-vanilla-like-enchantments-1-16-1-18.61693/) - Adds new enchantments.
- [Farm Protection for MC 1.16 - 1.20](https://www.spigotmc.org/resources/farm-protection-for-mc-1-16-1-20.85488/) - Disables crop breaking when jumping on top of them.
- [Levelled Mobs](https://www.spigotmc.org/resources/levelledmobs.74304/) - Adds mob leveling.
- [Overleveled Enchanter](https://www.spigotmc.org/resources/overleveled-enchanter.93379/) - Increases max enchantments level.
- [SpigotPing](https://www.spigotmc.org/resources/spigotping-added-in-tablist-ping.24419/) - Adds ping indicator to the tab menu.
## Data packs
### World Generation
- [Deeper Dark](https://modrinth.com/datapack/deeper_dark) - Adds new "Deeper Dark" dimension.
- [Dungeons and Taverns](https://modrinth.com/datapack/dungeons-and-taverns) - Adds new overworld structures.
- [Explorify](https://modrinth.com/datapack/explorify) - Adds new structures.
- [Hopo Better Mineshaft](https://modrinth.com/datapack/better-mineshaft)- Adds new mineshaft variants.
- [Hopo Better Ruined Portal](https://modrinth.com/datapack/hopo-better-ruined-portals)- Adds new ruined portal variants.
- [Hopo Better Underwater Ruins](https://modrinth.com/datapack/better-underwater-ruins)- Adds new ocean ruins variants.
- [Just Another Structure Pack](https://modrinth.com/datapack/just-another-structure-pack/) - Adds new structures.
- [Stellarity](https://modrinth.com/datapack/stellarity) - Overhauls the end dimension terrain generation.
- [Structory](https://www.stardustlabs.net/datapacks#Structory) - Adds new structures in addition to Terralith's.
- [Terralith](https://www.stardustlabs.net/datapacks#Terralith) - Overhauls overworld terrain generation with new biomes and structures.
- [Tidal Towns](https://modrinth.com/datapack/tidal-towns) - Adds new village to deep ocean biome.
- [Towns & Towers](https://www.planetminecraft.com/data-pack/towns-amp-towers-structure-overhaul/) - Adds new structures.
### Mobs
- [Nice Mobs Variants](https://www.planetminecraft.com/data-pack/nice-mob-variants/) - Adds new mobs variants, structures, and bosses.
### Other
- [Refined Advancements](https://modrinth.com/datapack/refined-advancements) - Updates and adds new advancements.
## Vanilla Tweaks
### Data packs
- Graves - Spawns a gravestone at the player's death location (stores inventory before death).
- Spawn - Enables the player to teleport to world spawn.
### Resource pack
#### Aesthetic
- Red Iron Golem Flowers - Adds red flower to the Iron Golem texture.
- Colorful Enchanting Table Particles - Adds colorful particles around enchanting tables.
- Unique Dyes - Differentiates each dye looks.
#### Variation
- Variated Bookshelf - Adds bookshelf texture variation.
#### Connected Textures
- Connected Bookshelf - Makes bookshelf textures connected to each other
#### Utility
- Brewing Guide - Adds guide to brewing stand GUI.
- Different Stems - Adds texture difference between pumpkin & melon stems.
- Diminishing Tools - Adds different textures based on tool durability.
- Hunger Preview - Adds hunger points info to food names.
- Ore Borders - Adds a border to the ore texture.
- Suspicious Sand & Gravel Borders - Adds a border to the suspicious sand and gravel texture.
- Visual Cauldron Stages - Adds visual indicator to cauldrons.
- Visual Honey Stages - Adds visual indicator to bee nests and bee hives.
#### Unobtrusive
- Borderless Glass - Removes glass border texture.
- Borderless Stained Glass - Removes stained glass border texture.
#### GUI
- Smoother Font - Makes the font smoother.