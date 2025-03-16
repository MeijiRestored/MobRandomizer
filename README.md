# Mob Randomizer Mod

A Minecraft mod that effectively randomizes mobs by remapping mob spawns.

https://github.com/user-attachments/assets/b9fdf4a9-7443-4ffa-8410-e996ae62c715

## Features

By randomly assigning every mob spawn another random mob, each mob will have another mob replace it for all its instances.

For example all piglins might get replaced by llamas.

Covers all types of mob spawns (natural, summoned, stuctures, ...).

## Details

The randomized mappings are created when the world is loaded. They are based on the world seed, so using the same seed will yield the same results.

Mobs that cannot spawn naturally (giant, illusioner, ...) are excluded.

## Installation

You can download the mod from [Modrinth](https://modrinth.com/mod/mobrandomizer/) or [CurseForge](https://www.curseforge.com/minecraft/mc-mods/mobrandomizer).

This mod uses Fabric and works with version 1.21.4 of Minecraft. It requires the [Fabric API](https://modrinth.com/mod/fabric-api/) to be present in the mods folder.

## Work in Progress

Older Minecraft versions may be implemented soon.

## Building from Source

Simply clone the repo and run `./gradlew build` or `./gradlew.bat build` (Windows) to build the mod jar.

It will be found in the `build/libs` directory.
