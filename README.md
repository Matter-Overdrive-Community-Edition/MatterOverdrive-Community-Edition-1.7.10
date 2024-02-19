![](BannerBlinks.gif)

![Discord](https://img.shields.io/discord/703124643149643818?logo=discord&link=https%3A%2F%2Fdiscord.gg%2FhQyAEZV) ![CurseForge Downloads](https://img.shields.io/curseforge/dt/557428?logo=curseforge&link=https%3A%2F%2Fwww.curseforge.com%2Fminecraft%2Fmc-mods%2Fmatter-overdrive-community-edition) ![Modrinth Downloads](https://img.shields.io/modrinth/dt/xNn9ASDj?logo=modrinth&link=https%3A%2F%2Fmodrinth.com%2Fmod%2Fmoce)

## Table of Contents
* [About](#about)
* [Features](#features)
* [Mod-Links](#mod-links)
* [Isues](#issues)
* [Building](#building)
* [IMC](#imc)

## About
Matter Overdrive is a Minecraft mod inspired by the popular Sci-fi TV series Star Trek. It dwells in the concept of replicating and transforming one type matter into another.
Although it may seem overpowered, Matter Overdrive takes a more realistic approach and requires the player to build a complex system before even the simplest replication can be achieved.

## Mod-Links
* [Modrinth](https://modrinth.com/mod/moce)
* [Curseforge](https://www.curseforge.com/minecraft/mc-mods/matter-overdrive-community-edition)
* [Discord](https://discord.gg/hQyAEZV)

## Features
* [Matter Scanner](https://mo.simeonradivoev.com/items/matter_scanner/), for scanning matter patterns for replication.
* [Replicator](https://mo.simeonradivoev.com/items/replicator/), for transforming materials.
* [Decomposer](https://mo.simeonradivoev.com/items/decomposer/), for braking down materials to basic form.
* [Transporter](https://mo.simeonradivoev.com/items/transporter/), for beaming up.
* [Phaser](https://mo.simeonradivoev.com/items/phaser/), to set on stun.
* [Fusion Reactors](https://mo.simeonradivoev.com/fusion-reactor/) and [Gravitational Anomaly](https://mo.simeonradivoev.com/items/gravitational_anomaly/)
* Complex Networking for replication control.
* Star Maps, with Galaxies, Stars and Planets
* [Androids](https://mo.simeonradivoev.com/android-guide/), become an Android and learn powerful RPG like abilities, such as Teleportation and Forefield Shields.


![Matter Overdrive Blocks and Items](https://mo.simeonradivoev.com/wp-content/uploads/2015/05/main_screenshot.png)

## Issues
https://github.com/Matter-Overdrive-Community-Edition/MatterOverdrive-Community-Edition-1.7.10/issues

## Building
1. Clone this repository via 
  - SSH `git clone git@github.com:Matter-Overdrive-Community-Edition/MatterOverdrive-Community-Edition-1.7.10.git` or 
  - HTTPS `git clone https://github.com/Matter-Overdrive-Community-Edition/MatterOverdrive-Community-Edition-1.7.10.git`
2. Setup workspace 
  - Decompiled source `gradlew setupDecompWorkspace`
  - Obfuscated source `gradlew setupDevWorkspace`
  - CI server `gradlew setupCIWorkspace`
3. Build `gradlew build`. Jar will be in `build/libs`
4. For core developer: Setup IDE
  - IntelliJ: Import into IDE and execute `gradlew genIntellijRuns` afterwards
  - Eclipse: execute `gradlew eclipse`
  
## IMC
See the example on [IMC](https://github.com/simeonradivoev/MatterOverdrive/blob/master/src/main/java/matteroverdrive/api/IMC.java) or you can see the [IMC handler](https://github.com/simeonradivoev/MatterOverdrive/blob/master/src/main/java/matteroverdrive/imc/MOIMCHandler.java).
