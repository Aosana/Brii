![Brii](https://staticdelivery.nexusmods.com/mods/1704/images/95501/95501-1688938116-621876061.png)

# Brii
A Wabbajack modlist for The Elder Scrolls V: Anniversary Edition, built and balanced around Simonmagus616's suite of mods.

# Table Of Contents

- [Table Of Contents](#tableofcontents)
- [Introduction](#introduction)
  - [List Contents](#list-contents)
  - [System Specs](#system-specs)
  - [Skyrim: Anniversary Edition (AE)](#skyrim-anniversary-edition-ae)
- [Installation](#installation)
  - [Pre-Installation](#pre-installation)
    - [Installing Microsoft Visual C++ Redistributable Package](#installing-microsoft-visual-c-redistributable-package)
    - [Steam Library](#steam-library)
    - [Set The Game's Language To English](#set-the-games-language-to-english)
    - [Clean Skyrim](#clean-skyrim)
    - [Start Skyrim](#start-skyrim)
  - [Using Wabbajack](#using-wabbajack)
    - [Preparations](#preparations)
    - [Downloading And Installing](#downloading-and-installing)
    - [Problems With Wabbajack](#problems-with-wabbajack)
    - [Pagefile In The Prevention Of Memory Crashes](#pagefile-in-the-prevention-of-memory-crashes)
- [Updating](#updating)
- [Startup](#startup)
- [Issues](#issues)

# Introduction

"Qethsegol vahrukiv paaz kulaas Yrsa, wo ensosin pah do Taazokaan voth ek Dun ahrk **brii**."

Brii is a Wabbajack modlist for The Elder Scrolls V: Anniversary Edition that is built and balanced around [SimonMagus616](https://www.nexusmods.com/skyrimspecialedition/users/67410746)'s suite of mods. With a plethora of vanilla-styled graphical enhancements, quest expansions, dialogue additions, and gameplay overhauls, Brii offers a relatively simplistic overhaul of The Elder Scrolls V: Skyrim Anniversary Edition that does not stray too far from the vanilla game.

## List Contents

Brii contains nearly 1,000 mods that have been patched and tested extensively with one another. For a full list of the mods found in Brii, check out the Load Order Library [here](https://loadorderlibrary.com/lists/brii)!

## System Specs

I develop and play Brii at 1080p resolution with the following system specs:

* CPU: AMD Ryzen 7 5700G with Radeon Graphics @ 3.80 GHz
* GPU: NVIDIA GeForce RTX 3080
* RAM: 32 GB

I get a consistent 60 FPS at every location in the game; however, your mileage may vary depending on your hardware. If you have issues with performance, please let me know as I may be able to help you!

## Skyrim: Anniversary Edition (AE)

Brii requires the _**full**_ Anniversary Edition of The Elder Scrolls V: Skyrim. If you have The Elder Scrolls V: Skyrim Special Edition, then you can purchase the Anniversary Edition upgrade [here](https://store.steampowered.com/app/1746860/The_Elder_Scrolls_V_Skyrim_Anniversary_Upgrade/). If you do not yet own The Elder Scrolls V: Skyrim Special Edition, then you can buy the entirety of The Elder Scrolls V: Skyrim Anniversary Edition [here](https://store.steampowered.com/sub/626153). Please ensure that your game is up-to-date and in English before attempting to install Brii!

# Installation

Installation is handled through [Wabbajack](https://www.wabbajack.org/#/) with a one-click install of the modlist; however, there are some pre-installation steps that must be followed for first-time users.

## Pre-Installation

These steps only need to be taken if you are installing Brii for the first time. If you are simply updating Brii to a newer version, jump straight to [Updating](#updating).

### Installing Microsoft Visual C++ Redistributable Package

This package is required for Mod Organizer 2, and you can download it from [Microsoft](https://support.microsoft.com/en-us/help/2977003/the-latest-supported-visual-c-downloads). Download the x64 version under "Visual Studio 2015, 2017 and 2019." [Direct link](https://aka.ms/vs/16/release/vc_redist.x64.exe) if you can't find it.

### Steam Library

If you have your Steam Library in Program Files, read and follow [this](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide) to put it somewhere else. Support will _not be provided_ to users who have their Skyrim installation in a Program Files folder. Folders such as Documents, Downloads, Desktop, or OneDrive are not acceptable places to move your Skyrim installation! Install your Steam Library to a drive's root, such as `C:\Steam Library`.

### Set The Game's Language To English

Wabbajack will fail to install Brii if your copy of The Elder Scrolls V: Skyrim Anniversary Edition is in any language other than English. All installed mods also assume you have an English copy of the game. I will not be able to provide support to users whose copy of The Elder Scrolls V: Skyrim Anniversary Edition is not in English.

To change your installation's language setting, open the Steam Properties window, navigate to the _Language_ tab, and select _English_ from the dropdown menu.

### Clean Skyrim

It is highly recommended that you uninstall the game through Steam, delete the game folder, and reinstall it. You should also clean up the `Skyrim Special Edition` folder in `Documents/My Games/` by deleting the contents within it.

[This](https://imgur.com/a/1dySo8q) is approximately what a clean Skyrim install should look like after a clean reinstallation. 

### Start Skyrim

Start the game and exit once you're in the main menu. This will ensure any settings files needed by Wabbajack are created in the game's root directory.

## Using Wabbajack

### Preparations

Download the release to a _working folder_. This folder **must not** be in a _common folder_ like your Desktop, Downloads or Program Files folder. It's best to create a Wabbajack folder near the root level of your drive like `C:/Wabbajack`.

Grab the latest release of Wabbajack from [here](https://github.com/wabbajack-tools/wabbajack/releases) and place the `Wabbajack.exe` file in the _working folder_.

### Downloading and Installing

The download and installation process can take a little while (an hour or more) depending on your system specs. Wabbajack will calculate the amount of threads it will use at the start of the installation. To have the highest amount of threads and thus the fastest speed, it is advised to have the working folder on an SSD.

1. Create a folder for the List at the root of your drive (like the Wabbajack folder) called "Brii"
2. Go back to your drive, and create a new folder, called "Wabbajack Downloads Folder". This specific folder can be on a different drive if you wish!
3. Download the latest release of `Brii` from the Github
4. Select the created folder in Step 1 as your installation folder
5. Select the created folder in Step 2 as your downloads folder
6. Click the Go/Begin button and wait for Wabbajack to finish

### Problems With Wabbajack

There are a lot of different scenarios where Wabbajack will produce an error. I recommend re-running Wabbajack before posting anything. Wabbajack will continue where it left off so you lose no progress.

Seriously, simply retrying the Wabbajack download fixes most problems.

**Could not download x**:

If a mod updates and the old files got deleted, it is impossible to download them. In this case, just wait until I update the mod list.

Some files are known to be problematic, and it is likely that those are the ones that failed. You can download them manually from their source and place the archives **AS IS** in your Wabbajack downloads folder.

**x is not a whitelisted download**:

This can happen when I update the modlist. Check if a new update is available, and wait if there is none.

**Wabbajack could not find my game folder**:

Wabbajack will not work with a non-English, GOG, or pirated version of the game. If you own the game on Steam, go back to the [Pre-Installation](#pre-installation) step.

### Pagefile In The Prevention Of Memory Crashes

Bigger Skyrim mod lists need a lot of memory, and when there is not enough available it may fail to allocate more. To fix this, you'll want to have a bigger [page file](https://www.ibm.com/docs/en/opw/8.2.0?topic=tuning-optional-increasing-paging-file-size-windows-computers). 

# Updating

If this mod list receives an update, please check the changelog before doing anything. Always back up your saves or start a new game after updating!

**Wabbajack will delete all files that are not part of the mod list when updating!**

This means that any additional mods you have installed on top of the mod list will be deleted. Your saves will be kept, but please check each update changelog to see if the update is save-compatible. Your downloads folder will not be touched!

Updating is like installing. You only have to make sure that you select the same path and tick the _overwrite existing mod list_ button.

# Startup

Open the installation folder and double-click on the program called `ModOrganizer.exe`.

Make sure the dropdown box on the right is set to `SKSE` and press the Run button.

# Issues

If you encounter an issue, please file a bug report and attach related images/videos along with your save file.


