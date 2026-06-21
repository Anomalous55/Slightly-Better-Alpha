# Alpha-QoL

![Minecraft Version](https://img.shields.io/badge/Minecraft-Alpha_1.1.2__01-brightgreen)
![License](https://img.shields.io/badge/License-MIT-blue)
![Platform](https://img.shields.io/badge/Platform-Java-orange)

[Alpha-QoL](https://anomalous55.github.io/Alpha-QoL/) is a lightweight vanilla optimization and quality-of-life mod for **Minecraft Alpha 1.1.2_01**. It focuses strictly on minor tweaks, backend modernization, and critical bug fixes while preserving the Vanilla Experience.

## NOTICE

A user has cloned this repo on Jun 11th, 2026, and is attempting to pass it off as their own work in clear violation of the MIT license. This (the repository you are on now, created by Anomalous55) is the original repository (created on Mar 13th, 2026). For your own safety, please do not download their work or attempt to run it as there is a very likely chance they may have modified my source code and introduced undefined behavior.

## Disclaimer

This project is not affiliated with Mojang or Microsoft.

It is intended for entertainment and educational purposes only. This repository does not intend to illegally distribute or encourage the illegal distribution of any proprietary Minecraft source code.

If any content is found to violate copyright or distribution policies, it will be removed immediately upon request by an authorized representative.

No copyright infringement is intended.

## About

Minecraft Alpha 1.1.2_01 is an incomplete version that has a far more brutal gameplay loop than the modern releases. The limitations and constraints on content make this an interesting and nostalgic version to play, but some bugs, glitches, and inconsistencies make this version downright unfair at some points. 

While there are existing mods that address these issues, many introduce additional mechanics or major gameplay changes that go beyond the scope of a minimal fix.

This project aims to provide **minimal improvement**, focused strictly on small quality-of-life fixes without adding any new features, implementing any of the various unused assets, or compromising the brutal vanilla experience, leaving room for player ingenuity to overcome the difficulty.

## Features

As of the most recent version:

### Additions
- Added XYZ Coordinates, World Seed, and a Day Counter to F3 Menu.
- Added an FPS Limiter slider to the options menu to set max framerate more accurately (Replaces the 'Limit FPS' option).
- Added the Inventory Shift-Clicking tweaks you are familiar with in modern versions.
- Added a secret method you may be familiar with from Beta to prevent farmland from being trampled.

### Tweaks
- You can now use text chat in Singleplayer Worlds.
- The game will now use your Minecraft Skin.
- You can now swap items of the same kind in the inventory.
- You can no longer accidentally eat food while your health is full.
- Cacti will no longer destroy dropped Cactus items.
- Doubled the durability of all tools and armor.
- Stack sizes of Wooden Doors, Iron Doors, and Signs have been increased to 16.
- Pickaxes, axes, and spades now correctly break their intended blocks.
- Clay is now 10% more common.
- Saddled Pigs will now drop their saddle when killed.
- Double slabs now drop both slabs when broken.
- Pressure Plates, Bookshelves, and Stairs now properly drop themselves when broken.
- Falling Snow in Winter Mode worlds now has a less obtrusive texture.
- Made the UI a little bit snappier (by fixing a bug where player inputs were skipped).
- Music now plays more often (Music is still semi-random with intervals of about 10-15 minutes instead of 20-25 minutes).

### Bug Fixes
- Fixed a major bug where world NBT Data resets upon rejoining a world.
- Fixed the Leaf Decay Bug.
- Fixed a bug where pressing a movement key and the Inventory key at the same time would cause you to move until the 'ESC' key is pressed.
- Fixed a bug where liquids would be placed when interacting with a block.
- Fixed a bug where instantly breakable blocks would be broken open returning to game from pause menu.
- Fixed a bug where multiple item shadows would render while Fancy Graphics are enabled.
- Fixed a bug where your footsteps all play at once after sneaking.
- Fixed the orientation of stairs, furnaces, chests, and double chests.
- Fixed the hitbox of stairs.
- Fixed a bug where Ore Generation is biased towards the positive coordinates.
- Fixed caves being cut off along Chunk Borders.
- Fixed a session.lock bug on OS's with aggressive CPU Schedulers.
- Fixed a crash when placing a Sign on a Cactus.
- Fixed torch placement when snow and a ledge are present.
- Fixed Mob Spawn Behavior.
- Fixed Slime Chunk generation.
- Removed Herobrine.

## Installation

Download the latest release ***[here](https://github.com/Anomalous55/Alpha-QoL/releases)***.
Or on ***[Modrinth](https://modrinth.com/mod/alpha-qol)***.

### Method 1 (MultiMC/Prism)

- Create an instance of Alpha 1.1.2_01 in MultiMC/Prism.
- Select your instance.
- Click Edit > Version > Minecraft > Add to Minecraft.jar
- Select the zip file.

### Method 2 (Self Patch)

- Open your version.jar file using an archive editor. 
- Delete META-INF then add the mod files from the zip file into it, overwriting existing files when prompted.

Launch the game and enjoy!
