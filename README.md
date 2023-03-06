
# awesome-anbernic

[![image](https://user-images.githubusercontent.com/44711271/222904252-84ba4888-779b-49f5-8229-1a0d9c9ab6f7.png)](https://github.com/dag7dev/awesome-anbernic/blob/master/README.md)

Awesome list for Anbernic consoles, mainly focused on OSes.

![image](https://user-images.githubusercontent.com/44711271/222904234-f01fb574-a42d-4b07-b5d9-48c47ea8af28.png)

## Index

- [awesome-anbernic](#awesome-anbernic)
  - [Disclaimer](#disclaimer)
- [Getting Started](#getting-started)
  - [Models](#models)
    - [List of models](#list-of-models)
    - [Naming convention](#naming-convention)
  - [Tech specs](#tech-specs)
  - [First steps](#first-steps)
    - [Charging your console](#charging-your-console)
- [Software](#software)
  - [OS](#os)
  - [Frontend](#frontend)
  - [Games and homebrew](#games-and-homebrew)
    - [What to play](#what-to-play)
    - [Homebrews and games](#homebrews-and-games)
  - [Tools](#tools)
- [Hardware](#hardware)
  - [Hardware mod](#hardware-mod)
- [Misc](#misc)
  - [Useful links](#useful-links)
    - [[NDS] Games playable by one screen only](#nds-games-playable-by-one-screen-only)
  - [FAQ and troubleshooting](#faq-and-troubleshooting)

## Disclaimer
>
> We are not responsible for general hardware malfunctions, software, data loss, or anything else that may harm you or your devices
> All software and hardware modifications are at your own risk
> All links shown are provided without warranty, and we are not affiliated in any way with any products or stores.

# Getting started

## Models

### List of models

- RG350M/P
- RG280M/V
- RG351P/M/V/MP
- RG552
- RG503
- RG505
- RG353P/V/VS
- RG35xx
- WIN600

No longer sold (hard to find):

- RG300
- RG300X
- RetroGame RS-97
- RetroGame RS-97 Plus

### Naming convention

Naming is unsure, but basing our knowledge on [this reddit thread](https://www.reddit.com/r/ANBERNIC/comments/z0dbui/anbernic_models_naming/):

- model's name scheme is RGXXYZZ

where

- XX - size of screen
- Y - processor
  - 0 = JZ4770
  - 1 = RK3326
  - 2 = RK3399
  - 3 = RK3366
- Z - version (optional)
  - P plastic
  - M metal
  - MP metal premium
  - V vertical
  - S single os

RG552 and RG505 are some of Anbernic consoles that doesn't follow in some case these "rules".

## Tech specs

| Model                | Processor                                                            | GPU                        | RAM   | Resolution  | Screen Size              | Aspect Ratio | Stock OS                  | Weight | Battery      | Price       |
| -------------------- | -------------------------------------------------------------------- | -------------------------- | ----- | ----------- | ------------------------ | ------------ | ------------------------- | ------ | ------------ | ----------- |
| RG350                | Ingenic JZ4770 (1GHz, Dual-core)                                     | Vivante GC860              | 512MB | 320 x 240   | 3-Inches (IPS)           | 3:2          | OpenDingux                | 160g   | 2500mAh      | $89.99      |
| RG350M               | Ingenic JZ4770 (1GHz, Dual-core)                                     | Vivante GC860              | 512MB | 640 x 480   | 3.5-inches (IPS)         | 4:3          | OpenDingux                | 255g   | 2500mAh      | $169.99     |
| RG350P               | Ingenic JZ4770 (1GHz, Dual-core)                                     | Vivante GC860              | 512MB | 320 x 240   | 3-inches (IPS)           | 3:2          | OpenDingux                | 170g   | 2500mAh      | $89.99      |
| RG280M               | Ingenic JZ4770 (1GHz, Dual-core)                                     | Vivante GC860              | 512MB | 320×480     | 2.8-inches               | 3:2          | OpenDingux                | 205g   | 2500mAh      | $109.99     |
| RG280V               | Ingenic JZ4770 (1GHz, Dual-core)                                     | Vivante GC860              | 512MB | 320×480     | 2.8-inches               | 3:2          | OpenDingux                | 120g   | 2100mAh      | $79.99      |
| RG351P               | Rockchip RK3326 (1.6GHz, quad-core)                                  | Mali-G31 MP2               | 1GB   | 320 x 480   | 3.5-inches               | 3:2          | EmuElec                   | 160g   | 3500mAh      | $99.99      |
| RG351M               | Rockchip RK3326 (1.6GHz, quad-core)                                  | Mali-G31 MP2               | 1GB   | 320 x 480   | 3.5-inches               | 3:2          | EmuElec                   | 260g   | 3500mAh      | $139.99     |
| RG351V               | Rockchip RK3326 (1.6GHz, quad-core)                                  | Mali-G31 MP2               | 1GB   | 640 x 480   | 3.5-inches               | 4:3          | EmuElec                   | 200g   | 3900mAh      | $114.99     |
| RG351MP              | Rockchip RK3326 (1.6GHz, quad-core)                                  | Mali-G31 MP2               | 1GB   | 640 x 480   | 3.5-inches               | 4:3          | EmuElec                   | 267g   | 3500mAh      | $149.99     |
| RG552                | Rockchip RK3339 (1.8GHz, hexa-core)                                  | Mali T860 GPU              | 4GB   | 1920 x 1152 | 5.3-inches               | 5:3          | Android 7.1               | 367g   | 6400mAh      | $230        |
| RG503                | Rockchip RK3566 (1.8GHz, hexa-core)                                  | Arm Mali-G52               | 1GB   | 960 x 544   | 4.95-inches (OLED)       | 16:9         | Linux                     | 235g   | 3500mAh      |             |
| RG505                | Unisoc Tiger T618                                                    | Mali-G52 MP2               | 4GB   | 960 x 544   | 4.95-inches (OLED) Touch | 16:9         | Android 12                | 286g   | 5000mAh      | $157.99     |
| RG353M               | Rockchip RK3566 (1.8GHz, hexa-core)                                  | Mali-G52 MP2               | 2GB   | 640 x 480   | 3.5-inches               | 4:3          | Linux & Android 11        | 232g   | 3500mAh      |             |
| RG353P               | Rockchip RK3566 (1.8GHz, hexa-core)                                  | Mali-G52 MP2               | 2GB   | 640 x 480   | 3.5-inches               | 4:3          | Linux & Android 11        | 209g   | 3500mAh      |             |
| RG353V               | Rockchip RK3566 (1.8GHz, hexa-core)                                  | Mali-G52 MP2               | 2GB   | 640 x 480   | 3.5-inches               | 4:3          | Linux & Android 11        | 193g   | 3200mAh      | $132        |
| RG353VS              | Rockchip RK3566 (1.8GHz, hexa-core)                                  | Mali-G52 MP2               | 1GB   | 640 x 480   | 3.5-inches               | 4:3          | Linux                     | 193g   | 3200mAh      | $109        |
| RG35xx               | Rockchip RK3566 (1.8GHz, hexa-core)                                  | PowerVR SGX544MP quad-core | 256MB | 640 x 480   | 3.5-inches (IPS)         | 4:3          | Linux                     | 165g   | 2100mAh      | $89.99      |
| WIN600               | AMD Athlon Silver 3020e (1.2Ghz) or AMD Athlon Silver 3050e (1.4Ghz) | AMD Radeon RX Vega 3       | 8GB   | 1280 x 720  | 5.94-inches (touch)      | 16:9         | Win10 - SteamOS - Linux | 490g   | 4500mAh \* 2 | $300 - $475 |
|                      |                                                                      |                            |       |             |                          |              |                           |        |              |             |
| Historical Purposes  |                                                                      |                            |       |             |                          |              |                           |        |              |             |
| RG300                | Ingenic JZ4760B (1GHz, Dual-core)                                    | ?                          | 128MB | 960 x 480   | 3-inches                 | 2:1          | OpenDingux                | 350g   | 1800mAh      | $50.00      |
| RG300X               | Ingenic JZ4770 (?GHz, Dual-core)                                     | Vivante GC860              | 512MB | 640 x 480   | 3.5-inches (IPS)         | 4:3          | OpenDingux                | 255g   | 2500mAh      | $79.99      |
| RetroGame RS-97 Plus | Ingenic JZ4760 (528MHz - 600MHz)                                     | \-                         | 128MB | 320 x 480   | 3-inches                 | 4:3          | OpenDingux                | 133g   | 1800mAh      |             |
| RetroGame RS-97      | Ingenic JZ4760 (528MHz - 600MHz)                                     | \-                         | 128MB | 320 x 480   | 3-inches                 | 4:3          | OpenDingux                | 133g   | 890mAh       |             |

## First steps

- Replace included SD card with renowned brands immediately. Included SD card are generally cheap and error-prone.
- Verify you're using the correct charging block.
- (optional) Flash custom firmware to have more flexibility.
- Charge your console: NEVER ever use a fast charger! **Use 5V/1A only**.

### Charging your console

Always shut it down and connect the charger.

NEVER ever use a fast charger! **Use 5V/1A only**.

Otherwise, you will permanently damage your battery.

Also, if you have HDMI output, some users have reported that they've damaged their units while outputting on a HDMI screen and charging at the same time.

Since this is in doubt, do not attempt to do this, the best way to avoid problems is to shut off your console and connect the charger.

In case you decide to both output on HDMI screen and charge at the same time, proceed at your own risk!

# Software

## OS

General facts found while browsing:

- Nintendo DS and Nintendo 64 emulation works best on Android.
- ArkOS is considered as more minimalistic and stable than JELOS (or uOS)
- Unless you'd like to have something tinkerable, you should go with Stock OS
- JELOS (uOS) controller config is believed to be hard; it still doesn't support sleep mode.

| OS Name                                                                                                                                                                                                         | Description                                                                                                                                                                                                                          | RG35xx | RG353P/M/V/VS | RG351P/M/V/MP | RG503 | RG552        | RG505 | RG300X | RG280M/V | RG350/M/P | WIN600                        | RG-300 | RetroGame RS-97 Plus | RetroGame RS-97 |
| --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ------ | ------------- | ------------- | ----- | ------------ | ----- | ------ | -------- | --------- | ----------------------------- | ------ | -------------------- | --------------- |
| [Linux Stock](https://win.anbernic.com/download/)                                                                                                                                                               | Stock firmware. Everything’s barely playable                                                                                                                                                                                         | ✅      | ✅             | ✅             | ✅     | ✅ (batocera) | ❌     | ❌      | ❌        | ❌         | ✅ (Linux or Win10 or SteamOS) | ❌      | ❌                    | ❌               |
| [Android Stock](https://win.anbernic.com/download/)                                                                                                                                                             | Android Stock firmware.                                                                                                                                                                                                              | ❌      | ✅ (not VS)    | ❌             | ❌     | ✅            | ✅     | ❌      | ❌        | ❌         | ❌                             | ❌      | ❌                    | ❌               |
| OpenDingux Stock                                                                                                                                                                                                | OpenDingux Stock Firmware.                                                                                                                                                                                                           | ❌      | ❌             | ❌             | ❌     | ❌            | ❌     | ✅      | ✅        | ✅         | ❌                             | ✅      | ✅                    | ✅               |
|                                                                                                                                                                                                                 |                                                                                                                                                                                                                                      |        |               |               |       |              |       |        |          |           |                               |        |                      |                 |
| [RetroFW](http://www.retrofw.com/)                                                                                                                                                                              | It allows you to play a wide variety of consoles and computers thanks to numerous emulators available to it as well as a number of popular videogame ports.                                                                          | ❌      | ❌             | ❌             | ❌     | ❌            | ❌     | ❌      | ❌        | ❌         | ❌                             | ✅      | ✅                    | ✅               |
| [ArkOS](https://github.com/christianhaitian/arkos/wiki)                                                                                                                                                         | Retroarch + Emustation frontend                                                                                                                                                                                                      | ✅      | ✅             | ✅             | ✅     | ❌            | ❌     | ❌      | ❌        | ❌         | ❌                             | ❌      | ❌                    | ❌               |
| [JELOS](https://github.com/JustEnoughLinuxOS/distribution)                                                                                                                                                      | Uncertain support for Anbernic builds. See UnofficialOS for more…                                                                                                                                                                    | ❌      | ✅             | ❌             | ✅     | ❌            | ❌     | ❌      | ❌        | ❌         | ❌                             | ❌      | ❌                    | ❌               |
| [UnofficialOS](https://github.com/RetroGFX/UnofficialOS)                                                                                                                                                        | JELOS fork. Retroarch + Emustation frontend                                                                                                                                                                                          | ❌      | ✅             | ❌             | ✅     | ❌            | ❌     | ❌      | ❌        | ❌         | ❌                             | ❌      | ❌                    | ❌               |
| [MinUI](https://github.com/shauninman/union-minui)                                                                                                                                                              | Minimal frontend. minarch + libretro cores                                                                                                                                                                                           | ✅      | ❌             | ❌             | ❌     | ❌            | ❌     | ❌      | ❌        | ❌         | ❌                             | ❌      | ❌                    | ❌               |
| [AmberELEC](https://github.com/AmberELEC/AmberELEC)                                                                                                                                                             | fork of EmuELEC which is based on CoreELEC, Lakka, and Batocera                                                                                                                                                                      | ❌      | 🔮            | ✅             | ❌     | ✅            | ❌     | ❌      | ❌        | ❌         | ❌                             | ❌      | ❌                    | ❌               |
| [TheRetroArena](https://techtoytinker.com/handheld-corner)                                                                                                                                                      | Retropie’s Fork for handheld. Features depending on your model.                                                                                                                                                                      | ❌      | ✅             | ✅             | ✅     | ❌            | ❌     | ✅      | ✅        | ✅         | ✅                             | ❌      | ❌                    | ❌               |
| [Lakka](https://www.lakka.tv/get/linux/)                                                                                                                                                                        | Linux OS RetroArch and LibreELEC based.                                                                                                                                                                                              | ❌      | ❌             | ✅             | ❌     | ❌            | ❌     | ❌      | ❌        | ❌         | ❌                             | ❌      | ❌                    | ❌               |
| [Batocera](https://batocera.org/download)                                                                                                                                                                       | Batocera.linux is an open-source and completely free retro-gaming distribution that can be copied to a USB stick or an SD card with the aim of turning any computer/nano computer into a gaming console during a game or permanently | ❌      | \*            | ✅             | \*    | ✅            | ❌     | ❌      | ❌        | ❌         | ✅                             | ❌      | ❌                    | ❌               |
| [Garlic OS](https://www.patreon.com/posts/garlicos-for-76561333)                                                                                                                                                | RetroArch port for RG35XX, with fully working sleep mode, improved button mappings, a whole new user interface and several under-the-hood bugfixes                                                                                   | ✅      | ❌             | ❌             | ❌     | ❌            | ❌     | ❌      | ❌        | ❌         | ❌                             | ❌      | ❌                    | ❌               |
| [Adam](https://github.com/eduardofilo/RG350_adam_image)                                                                                                                                                         | Custom firmware EmuStation for 350/350P, 280MV, 300X                                                                                                                                                                                 | ❌      | ❌             | ❌             | ❌     | ❌            | ❌     | ✅      | ✅        | ✅         | ❌                             | ❌      | ❌                    | ❌               |
| [RogueCFW](https://github.com/Ninoh-FOX/RG350-ROGUE-CFW)                                                                                                                                                        | Rogue CFW for RG350                                                                                                                                                                                                                  | ❌      | ❌             | ❌             | ❌     | ❌            | ❌     | ❌      | ❌        | ✅         | ❌                             | ❌      | ❌                    | ❌               |
| \* in theory is compatible since the builds are for generic chipsets, not for a specific one. The official OS website doesn't however states "this OS is compatible with this console". It needs more research. |                                                                                                                                                                                                                                      |        |               |               |       |              |       |        |          |           |                               |        |                      |                 |

## Frontend

Here's a list of non-exhaustive frontend that you can use with your Anbernic:

- [EmulationStation](https://github.com/Aloshi/EmulationStation): A graphical and themeable emulator front-end that allows you to access all your favorite games in one place, even without a keyboard!
- [Android] [Launchbox](https://www.launchbox-app.com/): box-art-based games database and launcher for DOSBox, emulators, arcade cabinets, and PC Games
- [Android] [Daijishou](https://github.com/magneticchen/Daijishou): Daijishō is a retro launcher that let you manage your retro games libraries. Daijishō cares about integrated experience, expansibility, aesthetic and pragmatical usabilities let you focus on games itself. It will be updated continuously in the future based on users responds and my own retro gaming experience in my free time. Beware it does not come with emulators.
- [Opendingux] [SimpleMenu](https://github.com/fgl82/simplemenu/releases):  Simple menu launcher for the new Bittboy, Pocket Go, RetroFW and OpenDingux devices

## Games and homebrew

### What to play

- [/v/ Recommended Games](https://vsrecommendedgames.miraheze.org/wiki/Main_Page)

### Homebrews and games

- [Romhacking.net](https://www.romhacking.net/homebrew/) the evergreen romhacking.net website
- [Homebrew Hub (GBDev.io)](https://hh.gbdev.io/) massive showcase of games and demos [also available for GBA](https://hh.gbdev.io/games/gba)
- [PS1 Homebrew](https://www.psx-place.com/forums/ps1-homebrew.48/) historical forum with tons of psx homebrew
- [N64Squid.com homebrew curated list](https://n64squid.com/homebrew/) a curated n64 homebrew list by n64squid
- [Gamebrew.org](https://www.gamebrew.org/wiki/List_of_DS_homebrew_applications) collaborative wiki for nds homebrew games and ports

## Tools

- [PortMaster](https://github.com/christianhaitian/PortMaster): A simple tool that allows you to download various game ports that are available for 351Elec/AmberElec, ArkOS, JelOS, RetroOZ, TheRA, and UnofficialOS for the RK3326 and RK3566 devices and the RG552.

- [AnberPorts](https://github.com/krishenriksen/AnberPorts): AnberPorts for Anbernic RG351P/M and RG351V running ArkOS, 351elec and The RA. The project is on hold, so it is advised to use **PortMaster**.

- [ThemeMaster](https://github.com/JohnIrvine1433/ThemeMaster) An EmulationStation theme manager for small screen devices running [ArkOS](https://github.com/christianhaitian/arkos), [RetroOZ](https://github.com/southoz/RetroOZ), [TheRA](https://techtoytinker.com/theretroarena), [JELOS](https://github.com/JustEnoughLinuxOS/distribution) or [UnofficialOS](https://github.com/RetroGFX/UnofficialOS).

- [Emulationstation-OGA-Theme-Gallery](https://github.com/Jetup13/Emulationstation-OGA-Theme-Gallery): Emulationstation theme gallery that links to themes that are compatible on small screen devices such as OGA, OGS, Gameforce Chi, RGB10, RGB10MAX, RK2020, RG351p/m, RG351v, and RG503.

# Hardware

## Hardware mod

- [Arrow fix - d-pad fix - Youtube](https://www.youtube.com/watch?v=-vl3qyifYJM)
- [RG350] [3D Printable Anbernic RG350 abxy buttons](https://www.thingiverse.com/thing:4000064)
- [RG350] [3D Printable Anbernic RG350 stick](https://www.thingiverse.com/thing:3963163)
- [RG350] [Screen 350M on RG350](https://retrogamecorps.com/2020/09/16/guide-install-the-rg350m-screen-on-your-rg350/)
- [RG351P] [3D Printable Dock](https://www.thingiverse.com/thing:4780269)
- [RG351P] [Add Wifi Module](https://youtu.be/lBEAIU5fn0Q)
- [RG35xx] [Better button "BetterButtons" mod (Etsy shop)](https://www.etsy.com/listing/1398432049/better-buttons-for-rg35xx)
- [RG353] [3D Printable Clamshell](https://www.thingiverse.com/thing:5861679)
- [RG350] [RG351] [Grip remover](https://youtu.be/5URkOzxSaRE)
- [RG353] [Custom skin overlay](https://www.etsy.com/ca/listing/1333542850/anbernic-rg353v-custom-skinoverlay)
- [RG353] [Better shoulder buttons](https://www.etsy.com/ca/listing/1353958841/better-shoulder-buttons-for-rg353v)
- Misc for ANBERNIC consoles (generic sellers)
  - [SakuraRetroModding](https://www.etsy.com/ca/shop/SakuraRetroModding)
  - [JP Only] [Various-booth](https://various-booth.booth.pm/)

# Misc

## Useful links

- [Retrosizer](https://retrosizer.com/) compare the size of handheld devices and see how certain systems will appear on their screens. You can drag the devices and rotate them etc. (controllers too)
- [Google Sheet with technical specs about other consoles](https://docs.google.com/spreadsheets/d/1irg60f9qsZOkhp0cwOU7Cy4rJQeyusEUzTNQzhoTYTU/edit?usp=drivesdk)
- [SNES Fastrom patches](https://docs.google.com/spreadsheets/d/1gUB4N0-tM7Ln-9ZMwkp_T7bwb4tDAMI6ciioYMxXzSk/edit#gid=0) - [more info on FastROM project](https://github.com/VitorVilela7/fastrom)
- [Repo of PSP settings for XX3 devices](https://gitlab.com/k-tec/rk3566-ppsspp-settings)
- [Improved PSP emulation on supported Anbernic devices](https://www.reddit.com/r/RG353V/comments/1106acz/comment/j88op01/?utm_source=share&utm_medium=web2x&context=3)
- [Connect an external device by OTG](https://retrogamecorps.com/2020/08/29/guide-external-gamepad-support-for-the-rg350/)
- [RG353V] [Reddit Megathread about CFW (ArkOS, JELOS)](https://www.reddit.com/r/RG353V/comments/y6p2bj/firmware_megathread_arkos_jelos_stock_firmware/)
- [RG351P] [RG351P PPSSPP Settings and Compatibility List](https://github.com/jserodio/rg351p-ppsspp-settings)
- [RG553] [RG552 Fix rewind, retroarch overrides, button numbers](https://gist.github.com/maddox/fca7fa3f00265eb15d23ed4556e4c78e)
- [RG350] [HDMI Output Patch for old console](https://retrogamecorps.com/2020/08/18/rg350-hdmi/)

### NDS Games playable by one screen only

Tons of patches are available for a lot of games.

However these could be particularly useful since some of Anbernic consoles support NDS emulation.

Titles have been aggregated from these links: [link1](https://www.reddit.com/r/EmulationOnAndroid/comments/61tbsx/lets_make_a_list_of_nontouchmostlygamepad/) - [link2](https://www.reddit.com/r/retroid/comments/i8jqfj/gamepadfriendly_ds_games/) - [link3](https://www.reddit.com/r/RetroPie/comments/7120yx/ds_games_that_dont_use_touch_screen/)

- Advance Wars: Days of Ruin
- Advance Wars: Dual Strike
- Aliens: Infestation
- Asphalt: Urban GT
- Assassin's Creed II: Discovery
- Castlevania: Dawn of Sorrow (with [No Touchscreen patch](http://www.romhacking.net/hacks/3408/))
- Castlevania: Order of Ecclesia
- Castlevania: Portrait of Ruin
- Custom Robo Arena
- Disgaea DS
- Dragon Quest 4/5/6/9
- Dragon Quest Heroes: Rocket Slime! (except optional minigames)
- Dragon Quest Monsters: Joker 1/2
- Etrian Odyssey 1/2/3
- Final Fantasy III / IV
- Final Fantasy Tactics: Advance 2
- Fire Emblem: Shadow Dragon
- Front Mission
- Geometry Wars: Galaxies
- Infinite Space
- Kingdom Hearts Re: Coded
- Kingdom Hearts: 358/2 Days
- Kirby: Squeak Squad
- Kirby: Super Star Ultra
- Lunar Knights
- Mario & Luigi: Partners in Time / Bowser's Inside Story
- Mario Kart DS
- Mega Man ZX / ZX Advent
- Mega Man Zero Collection
- MegaMan series
- Metal Slug 7 (though Metal Slug XX on PSP seems to be a superior version of this game, and runs perfectly in lr-ppsspp)
- N+
- New Super Mario Bros. (except "reserve" item)
- Phantasy Star 0
- Phoenix Wright series
- Pokemon Mystery Dungeon Serie
- Radiant Historia
- Rhythm Heaven (using [button patch](https://www.romhacking.net/hacks/4824/))
- Rune Factory 3
- Sands of Destruction
- Shin Megami Tensei: Devil Survivor / Devil Survivor 2
- Shin Megami Tensei: Strange Journey
- SolatoRobo: Red the Hunter
- Sonic Rush (except special stages)
- Spider-Man: Web of Shadows
- Suikoden Tierkreis
- Super Mario 64 DS (only after you've saved in-game at least once - on the first playthrough, you're required to touch the star - also, optional minigames require touch)
- Super Robot Taisen OG Saga: Endless Frontier
- Tales of Innocence
- Tetris DS (no minigames)
- The Legend of Zelda: Phantom Hourglass (using [D-Pad Patch](https://www.romhacking.net/hacks/786/))
- The Legend of Zelda: Spirit Tracks (using [D-Pad Patch](https://www.romhacking.net/hacks/2235/))
- Umihara Kawase Shun
- Valkyrie Profile: Covenant of the Plume
- Yoshi's Island DS
- Yugioh 5d's games

## FAQ and troubleshooting

- Refund policy
  - [Ambernic, from their homepage](https://anbernic.com/pages/refund-policy):
  15-Day Refund Policy - Undamaaed products can be refunded within 15 days after the delivery date(applicable only in selected destination countries).Once the item is returned to Anbernic warehouse for inspection，the refund process will begin in 3 working days. Refunds will be credited within 5-10 working days. - JP EU and US.
  - Everyone else: check their policy on their website

- D-pad doesn't work / dpad works bad.
  - [Electrical tape mod](https://www.youtube.com/watch?v=-vl3qyifYJM) this mainly occurs while playing Pokemon Games

- Saving doesn't seem to work
  - **Replace your SD Card with a reputable brand**. Best ones: Samsung, Sandisk, Lexar, Kingston, Transcend.

- Battery upgrade / batteries / where battery compatible with...
    1) Check the specs of the target battery match with the original one (not considering mAh)
    2) Check their connectors
    3) buy

- Single or dual sd card setup?
  - As long as you just wanna play, you're fine with just one OS and don't have the need of having a lot of large games, you don't need to have a dual SD card setup. Make note that you will need to invest in a decent SD Card to prevent data loss or unintended behaviors.

- Shell replacement / custom shell
  - Currently ANBERNIC **doesn't sell** separate shells for their console.

- Strange LED behavior / battery doesn't work
  - either open your console, took out the batter connector for a minute or two, rensemble back and hope that everything works OR
  - the battery is dying. You've permanently damaged your console while using a high voltage charger or something else has happened. **ALWAYS USE A 5V/1A charger!**

- Change battery low icon
  - Replace `battery_low.bmp.gz` in MISC.

- [JELOS] Where gamelist.xml of custom game collections are saved in JELOS?
  - `/storage/.emulationstation/collections/`
  - Samba share path: `\config\emulationstation\collections`

- [Adam CFW] [NES color palette] I was playing a game on the NES emulator and noticed I hit some button combo accidentally and it changed the color display. Any idea how to change it back to normal?

  - L2+dpad left/right will allow you to scroll through all the color pallete options. There are actually some really cool options here. [(source)](https://www.reddit.com/r/RG350/comments/11j7oyd/adam_image_nes_color_display/)
