# Wynncraft: Rekindled
[![Wynncraft Rekindled World Banner][1]][2]

[1]: https://cdn.modrinth.com/data/cached_images/838a9c58769a06b79203a2687415f2e15a856139.webp
[2]:  http://wynncraft.com "Redirect to homepage"

**If you are new to Wynncraft, click the banner above to learn more!**\
**Please take a quick look at the installation section!**

This modpack seeks to overhaul and optimize the Wynncraft server experience. It is updated to support Minecraft 1.21 and the Rekindled World update. Several custom mods and features were developed specifically for this modpack!

## Features

This modpack is designed to be feature rich while providing functionality and options. Several popular features such as shoulder surfing and dynamic crosshairs are present but easily disabled. This modpack is designed to be beginner friendly so anyone new to Wynncraft can install and start playing with easy to understand presets applied. More advanced users who use warring features will want to change these settings as they have been disabled for simplicity.
 
### Custom Main Menu & Loading Screen

This modpack features a fully custom main menu with custom music! There are 10 main menu variants each with matching music. The loading screen has also been customized. Watch the demonstration below:

[![Youtube Demonstration](https://img.youtube.com/vi/KP6yD7GRyTk/0.jpg)](https://www.youtube.com/watch?v=KP6yD7GRyTk)
 
### Dynamic Weather

Features a [dynamic weather engine](https://modrinth.com/mod/wynncraft-dynamic-weather) created specifically for this modpack! Rain or thunder can randomly occur throughout the map, and areas such as Nemract, Pirate Cove, the Dernal Jungle, and others experience more frequent weather conditions. Traverse through snowstorms in Nesaak, sandstorms in Almuj and other weather hazards! Coupled perfectly with the [Particle Rain](https://modrinth.com/mod/particle-rain) mod with custom settings.

![WynnWeather4](https://github.com/user-attachments/assets/ab469bc7-1b67-4001-87b4-7a564c8ca17d)


### Custom Wynntils Preset

Comes preloaded with a custom Wynntils preset designed with simplicity and beginners in mind. More advanced players are recommneded to import their own Wynntils settings.

![Wynntils Map](https://cdn.modrinth.com/data/cached_images/72a1c3b9d4decc3099276ef73a345e84e3d490eb.jpeg)
![Wynntils Quest Book](https://cdn.modrinth.com/data/cached_images/761feff2f647833da3f65c2a8dc89303720bb831.png)

### Shoulder Surfing

Comes with preset settings for the incredibly popular Shoulder Surfing mod!
![ShoulderSurfing3](https://github.com/user-attachments/assets/05f3bbdd-b865-4fdb-a702-aefb20bcff3c)


### Optimization

Achieves peak performance with a wide variety of all the most recent optimization mods. Any future optimization mods will be added as well! See modlist for more information.

### Other

This modpack includes wide variety of quality of life and visual upgrades.
- Bobby mod allows server render distances up to 256 chunks
- Several chunk loading mods improve performance and visuals
- Complementary Unbound shaders with custom settings retains vanilla-like style with improved visuals
- Many, many visual tweaks in mods and resource packs

Some mods are still in the process of getting ported to 1.21. There are several that are on track to be added as soon as they are ported.

## Installation

**IMPORTANT NOTE:** Due to filesize limitations on Modrinth, the Bobby config folder is hosted on the [GitHub releases page.](https://github.com/elijahjibben/wynncraft-rekindled-modpack/releases) For instructions to install it, please review the installation guide.\
**Common Issues**\
-**Crashing**\
Minecraft 1.21 is the first verion to use Java 21. If you experience a crash, make sure you are using Java 21.\
-**Menu is Glitchy/Clipping**\
This is an common issue when first starting the pack. Try pressing CTRL + Alt + R to reload the menu. Unfortunately, in some scenarios it is impossible to fix this.

<details>
<summary>Installation Guide</summary>

# Step One: Download the Modpack
There are three easy ways to download the modpack: The Modrinth app, Prism Launcher, Manually (Minecraft Launcher)

## Modrinth App
1. Download the [Modrinth App](https://modrinth.com/app) and sign in with your Microsoft/Minecraft account.
2. Press the Browse button and search for Wynncraft: Rekindled.
3. Install the modpack.
4. Navigate to the modpack's [GitHub Releases](https://github.com/elijahjibben/wynncraft-rekindled-modpack/releases) panel.
5. Download the file "bobby.zip". This allows you to increase your render distance beyond the server limit of 9 chunks.
6. Navigate to the Modrinth App's Library panel, and select Wynncraft: Rekindled -> Folder.
7. Follow Step Two to install the bobby configuration.

## Prism Launcher
1. Download [Prism Launcer](https://prismlauncher.org/) and sign in with your Microsoft/Minecraft account.
2. Download the .zip version of the modpack from the [GitHub Releases](https://github.com/elijahjibben/wynncraft-rekindled-modpack/releases) panel.
3. Drag and drop into the Prism Launcher menu.
4. Select "Ok"
5. Right click -> Rename if desired
6. Launch the game and follow Step Three.

## Manually (Minecraft Launcher)
1. Download the .zip version of the modpack from the [GitHub Releases](https://github.com/elijahjibben/wynncraft-rekindled-modpack/releases) panel.
2. Download the [Fabric Installer](https://fabricmc.net/use/installer/) and install for Minecraft 1.21, Loader Version 1.60.0.
3. Copy the .minecraft folder from the zip file to any location (Roaming recommended)
4. Rename the folder (.wynncraft recommended)
5. Open the Minecraft Launcher
6. Select Minecraft: Java Edition on the left panel
7. Select Installations -> New Installation
8. Select the custom game directory, and set version to the fabric-loader
9. Optional: Set Java arguments from -Xmx2G to higher to allocate more RAM
10. Optional: Download this pack icon to change the instance icon!\
[Rekindled Pack Icon](https://cdn.modrinth.com/data/cached_images/fd52f8703f66b28b37c2b1d782c1584ad4d90973.png)
11. Launch the game and follow Step Three.

# Step Two: Bobby Install
Extract the bobby file into the instance folder. Ensure the file is named:
```
.bobby
```
and contains a folder named:
```
play.wynncraft.com
```
It should look like this:\
![Bobby File Demonstration](https://cdn.modrinth.com/data/cached_images/471bf9ce4475b682f3028b6452bb3486396892de.gif)

# Step Three: Configurations
1. Bobby Update
As soon as you are in a world, type the following command into chat:
```
/bobby upgrade
```
This command is required to make bobby register the chunks saved in the instance directory.\
2. Configure Keybinds and Settings
Take a look through the keybinds menu! I recommend at least changing the "Cast 1-4 Spell" keybinds to suit your mouse/keyboard.\
Look at the Video Settings to suit your computer's performance.

</details>

## Modlist


<details>
<summary>Modlist</summary>

- [No Resource Pack Warnings](https://modrinth.com/mod/6xKUDQcB)
- [Chunks Fade In](https://modrinth.com/mod/JaNmzvA8)
- [Custom Splash Screen](https://modrinth.com/mod/BwFQLeCh)
- [Tiny Item Animations](https://modrinth.com/mod/wMkevcSR)
- [MixinTrace](https://modrinth.com/mod/sGmHWmeL)
- [FancyMenu](https://modrinth.com/mod/Wq5SjeWM)
- [Forge Config API Port](https://modrinth.com/mod/ohNO6lps)
- [Fabric Language Kotlin](https://modrinth.com/mod/Ha28R6CL)
- [Particle Rain](https://modrinth.com/mod/nrikgvxm)
- [Sodium Extra](https://modrinth.com/mod/PtjYWJkn)
- [Lithium](https://modrinth.com/mod/gvQqBUqZ)
- [Remove Hud But Not Hand!](https://modrinth.com/mod/MiPOIx6b)
- [Entity Model Features](https://modrinth.com/mod/4I1XuqiY)
- [Dynamic Crosshair](https://modrinth.com/mod/ZcR9weSm)
- [Shoulder Surfing Reloaded](https://modrinth.com/mod/kepjj2sy)
- [ClickThrough](https://modrinth.com/mod/ERHOxvaH)
- [Wakes](https://modrinth.com/mod/dlNu0RQY)
- [Debugify](https://modrinth.com/mod/QwxR6Gcd)
- [Mod Menu](https://modrinth.com/mod/mOgUt4GM)
- [YDM's Weapon Master](https://modrinth.com/mod/qi1sj2da)
- [Cull Particles](https://modrinth.com/mod/Cya14nsC)
- [Falling Leaves](https://modrinth.com/mod/WhbRG4iK)
- [More Culling](https://modrinth.com/mod/51shyZVL)
- [3d-Skin-Layers](https://modrinth.com/mod/zV5r3pPn)
- [Wynntils](https://modrinth.com/mod/dU5Gb9Ab)
- [EntityCulling](https://modrinth.com/mod/NNAgCjsB)
- [ClientSideNoteblocks](https://modrinth.com/mod/flmhXQgb)
- [Searchables](https://modrinth.com/mod/fuuu3xnx)
- [More Chat History](https://modrinth.com/mod/8qkXwOnk)
- [AmbientSounds](https://modrinth.com/mod/fM515JnW)
- [Server Pack Unlocker](https://modrinth.com/mod/PiuygVWJ)
- [FerriteCore](https://modrinth.com/mod/uXXizFIs)
- [Zoomify](https://modrinth.com/mod/w7ThoJFB)
- [Cloth Config v15](https://modrinth.com/mod/9s6osm5g)
- [Entity Texture Features](https://modrinth.com/mod/BVzZfTc1)
- [Melody](https://modrinth.com/mod/CVT4pFB2)
- [Sodium](https://modrinth.com/mod/AANobbMI)
- [Visuality](https://modrinth.com/mod/rI0hvYcd)
- [Barriers Don't Block Rain](https://modrinth.com/mod/fwmKUI9s)
- [Fabric API](https://modrinth.com/mod/P7dR8mSH)
- [Indium](https://modrinth.com/mod/Orvt0mRa)
- [fuy.gg](https://modrinth.com/mod/EMQzFaJ1)
- [ImmediatelyFast](https://modrinth.com/mod/5ZwdcRci)
- [Cubes Without Borders](https://modrinth.com/mod/ETlrkaYF)
- [Controlify](https://modrinth.com/mod/DOUdJVEm)
- [Krypton](https://modrinth.com/mod/fQEb0iXm)
- [Bobby](https://modrinth.com/mod/M08ruV16)
- [Architectury](https://modrinth.com/mod/lhGA9TYQ)
- [Concurrent Chunk Management Engine](https://modrinth.com/mod/VSNURh3q)
- [NotEnoughAnimations](https://modrinth.com/mod/MPCX6s5C)
- [Blur+ (Fabric)](https://modrinth.com/mod/NK39zBp2)
- [Animatica](https://modrinth.com/mod/PRN43VSY)
- [Continuity](https://modrinth.com/mod/1IjD5062)
- [Reese's Sodium Options](https://modrinth.com/mod/Bh37bMuy)
- [Enhanced Block Entities](https://modrinth.com/mod/OVuFYfre)
- [Iris](https://modrinth.com/mod/YL57xq9U)
- [Better Beds](https://modrinth.com/mod/kKwy3HU9)
- [Video Tape](https://modrinth.com/mod/LVTZtqlk)
- [BetterF3](https://modrinth.com/mod/8shC1gFX)
- [Nvidium](https://modrinth.com/mod/SfMw2IZN)
- [Wynncraft Dynamic Weather](https://modrinth.com/project/wynncraft-dynamic-weather)
- [YetAnotherConfigLib](https://modrinth.com/mod/1eAoo2KR)
- [Konkrete](https://modrinth.com/mod/J81TRJWm)
- [WaveyCapes](https://modrinth.com/mod/kYuIpRLv)
- [Chat Heads](https://modrinth.com/mod/Wb5oqrBJ)
- [CreativeCore](https://modrinth.com/mod/OsZiaDHq)
- [ModernFix](https://modrinth.com/mod/nmDcB62a)
- [Controlling](https://modrinth.com/mod/xv94TkTM)
- [Dynamic FPS](https://modrinth.com/mod/LQ3K71Q1)

</details>

## License and Affiliation
This modpack is licensed under the LGPL-3.0 license. This modpack is not affiliated with Wynncraft.
