![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World/refs/heads/main/images/Oblivion%202025-09-04%2018-41-26%20-%20Copy.webp)

<p align="center">
An Oblivion Wabbajack Modlist by Sasquatch.
</p>

<table style="border: none;">
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Wabbajack</a></td>
<td><a href="https://loadorderlibrary.com/lists/a-painted-world-2">Load Order Library</a></td>
<td><a href="https://discord.gg/dGP9Vy7QMG">Discord</a></td>
<td><a href="https://www.nexusmods.com/games/oblivion/collections/zznpcp">Nexus</a></td>
<td><a href="https://ko-fi.com/sasquatch678">Ko-Fi</a></td>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

---

# Overview

A Painted World is a complete overhaul of TES IV: Oblivion focused on stylized, timeless visuals, modernized combat, deeper RPG mechanics, and meaningful progression. Built around MOO and OOO, it greatly expands Cyrodiil with expanded cities, new and reworked locations, additional quests and factions, unique landscapes, and new lands such as Elsweyr.

The world is designed with immersion and roleplay at its core. It features a wide range of systems and slice-of-life activities, including crafting, animal taming, fishing, home building and decorating, and more. Nearly every aspect of the game has been carefully refined or expanded, with many custom additions to existing mechanics alongside entirely new systems.

## A Different Cyrodiil

You must be prepared to cast aside your previous notions about Cyrodiil.

The world no longer revolves around you, the player. Do not expect to be able to defeat every monster or NPC you encounter from level one. Familiar areas may now be far more dangerous, and you will sometimes be forced to retreat from enemies who are simply too powerful to defeat until you have grown stronger.

You will probably die more often.

However, if you have the ingenuity, skill, and luck to overcome the odds stacked against you, you will be justly rewarded for your bravery.

If you feel overwhelmed by the difficulty when you first enter this dangerous new world, do not be discouraged. Be cautious at first and upgrade your gear whenever possible. If you encounter overwhelming odds, run away and return later when you are stronger to reap revenge upon your foes.

Make use of the expanded combat system, broader spell variety, new religion system, and many other tools at your disposal. When necessary, seek help from other travelers and Imperial Legion patrols along the roads.

The farther you venture from civilization, the deadlier the enemies you will encounter and the greater the rewards. With every level, you will become stronger than before.

**Learn the world, prepare for what lies ahead, and don't give up.**

---

# Requirements & Compatibility

## Supported Game Version

Due to the need to clean master files and certain limitations with Wabbajack, A Painted World only supports:

* **Oblivion GOTY Deluxe**
* **Steam version**
* **English language**

**GOG and other languages are not supported.**

## Windows

Wabbajack and A Painted World fully support:

* Windows 10
* Windows 11
* Windows version **21H2 or newer**

LTSC, special variants, lightened editions, or other modified versions of Windows **will not work**.

## Storage

Running A Painted World from a hard disk drive or external drive is **strongly discouraged**.

A large amount of content is swapped at runtime, so fast storage and sufficient RAM are important for a smooth experience.

A SATA SSD or faster storage is recommended.

## Recommended System Requirements

| Component | Recommended                                                            |
| :-------: | :--------------------------------------------------------------------- |
|    CPU    | Quad-core Intel or AMD CPU                                             |
|    RAM    | 4GB DDR4 RAM                                                           |
|  Storage  | SATA SSD or higher                                                     |
|    GPU    | DirectX 9.0c and Vulkan compliant video card with at least 8GB of VRAM |

**Space required: ~115GB total**

---

# Installation

Installing A Painted World through Wabbajack is relatively painless and takes a fraction of the time required to build a modlist of this size yourself.

Before beginning, you must own a **Steam copy of Oblivion GOTY Deluxe Edition**.

Follow the steps below in order.

## 1. Pre-Installation

The following steps **must be completed before downloading A Painted World**.

### Install Required Runtimes

Install:

* [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe)
* [.NET Runtime v5 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.5-windows-x64-installer)

### Completely Remove Existing Oblivion Files

Fully uninstall Oblivion.

After uninstalling, manually delete:

* The Oblivion installation folder
* The Oblivion folder inside `Documents\My Games\`

This ensures that old files and configuration settings cannot interfere with the installation.

### Disable OneDrive

Fully disable OneDrive and any other programs that hook into user file locations.

### Reinstall Oblivion Outside Program Files

Reinstall Oblivion somewhere outside of `Program Files`.

A location such as:

```text
C:\Games
```

is recommended.

Avoid unnecessarily long file paths.

If you only have one drive and need another Steam library location, consider using LostDragonist's [SteamLibrary Setup Tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).

### Launch Oblivion Once

Start the game once after installation and allow it to perform its graphics check.

Do not worry about configuring the graphics settings. A Painted World will replace these settings during installation.

### Apply the 4GB Patch

Download and extract the [4GB Patch](https://www.nexusmods.com/oblivion/mods/45576?tab=files).

Run the patch executable on `Oblivion.exe` in your Oblivion installation folder.

### Disable Third-Party Antivirus

Remove or disable third-party antivirus software such as MalwareBytes or Webroot.

These programs can interfere with the installation and may prevent Wabbajack or Mod Organizer 2 from functioning correctly.

### Disable Overlays

Disable all:

* Steam overlays
* NVIDIA overlays
* Discord overlays

### Cap Your FPS

Cap your framerate to **60 FPS** through the NVIDIA Control Panel or AMD equivalent.

You may also want to force anti-aliasing through your graphics driver's control panel, as the in-game anti-aliasing option is not available.

---

# 2. Install Wabbajack

Once pre-installation is complete, download the [latest version of Wabbajack](https://github.com/wabbajack-tools/wabbajack/releases).

Place Wabbajack somewhere such as:

```text
C:\Games\Wabbajack
```

### Do not place Wabbajack:

* In `Program Files`
* On your Desktop
* In your Downloads folder

Installing Wabbajack on an SSD is recommended because it will improve installation speed.

> :warning: **IMPORTANT:** A Painted World will always require the **latest version of Wabbajack** unless a different version is specifically stated in the modlist's release information. :warning:

---

# 3. Download & Install A Painted World

Depending on your internet connection and computer, downloading and installing the list can take some time.

1. Open Wabbajack.
2. Select **Browse Modlists**.
3. Find **A Painted World**.
4. Press **Download** and wait for the modlist to download.
5. Set the installation folder to a location such as:

   ```text
   C:\APW
   ```
6. **Do not install the modlist to your Desktop or Downloads folder.**
7. The download location does not need to be on an SSD, although using an SSD will make installation somewhat faster.
8. Press the **Play** button to begin the installation.
9. Let Wabbajack finish.

Go pet your nearest fluffy animal while Wabbajack does its thing.

Alternatively, read through this README again.

Once installation finishes successfully, continue to [Post-Installation](#post-installation).

If installation fails, see [Installation Troubleshooting](#installation-troubleshooting).

---

# Installation Troubleshooting

Wabbajack may occasionally encounter problems while installing the list. The following covers some of the most common issues.

## Failed Downloads

### Missing Manual Downloads: `Oblivion.exe`

You did not apply the 4GB patch correctly.

Return to [Pre-Installation](#1-pre-installation) and carefully follow the instructions again.

### `x is not a whitelisted download`

This generally occurs when the modlist has recently been updated.

Check whether a newer version of A Painted World is available, or wait until an update announcement is posted.

### Wabbajack Could Not Find My Game Folder

Either:

* Make sure you own the supported Steam version of Oblivion GOTY Deluxe, or
* Return to [Pre-Installation](#1-pre-installation) and verify that Oblivion was installed correctly.

## Antivirus Reports a Virus

Modding tools and mod organizers are commonly flagged by antivirus software as false positives.

First, make sure you followed the antivirus instructions in [Pre-Installation](#1-pre-installation).

If you have, you can add an exclusion for Mod Organizer 2 in Windows Defender using [these instructions](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

---

# Post-Installation

> :warning: **IMPORTANT:** Your game may not work correctly or may constantly crash if the required post-installation steps are not completed. :warning:

## Set Your Resolution

Navigate to the installation folder and open:

```text
profiles/A Painted World/Oblivion.ini
```

Find:

```ini
iSize H
iSize W
```

Make sure these values match your monitor's resolution.

If they do not, change them to match your display and save the file.

**If you use the controller profile, you must also apply this resolution setting to that profile.**

## Add an Antivirus Exception

Modding tools and mod organizers are commonly flagged by antivirus software, including Windows Defender, as false positives.

Add an exception for your A Painted World installation folder.

For Windows Defender, follow [these instructions](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

---

# ReShade

ReShade is optional.

Due to the way ReShade interacts with DXVK and Vulkan, anyone who wants to use the custom ReShade configuration included with A Painted World must install the ReShade binaries themselves.

Download ReShade from:

https://reshade.me/

When installing:

1. Point the installer to `Oblivion.exe` inside the **Stock Game** folder of your A Painted World installation.
2. Select **Vulkan** when prompted.
3. Uncheck all effects when prompted, as the required effects are already included with the modlist.

Once installed, ReShade will automatically read the preset included with A Painted World.

---

# Starting A Painted World

Open your A Painted World installation folder and launch:

```text
ModOrganizer.exe
```

Make sure the dropdown on the right is set to:

**Oblivion**

Then press **Run**.

## Character Creation

You will begin the game aboard a ship, inside a cabin where you can choose your race and create your character as normal.

Once you have finished all of the prompts, give the game approximately **30 seconds** to finish loading the scripts it needs.

You are free to loot anything you want from the ship. There is a table containing food and bottles of wine on the dresser.

When you have finished creating your character, find the **passport** on the table across from the dresser.

Interact with the passport once to review and change any choices you have already made.

Interact with it again to finalize your character.

Finally, **sleep in the bed**.

You will then be prompted to choose your starting city. Depending on your class and skill selections, you will also receive appropriate starting equipment and spells.

What happens next is entirely up to you.

The world is open for you to explore, so choose your path and begin your adventure.

---

# Controller Setup

A Painted World includes a dedicated controller profile.

To use a controller:

1. Open **Mod Organizer 2**.
2. Click the profile dropdown at the top of the application.
3. By default, this will be set to **A Painted World**.
4. Select **A Painted World - Controller** instead.

Each profile uses its own `Oblivion.ini`.

**Make sure you set your resolution for the controller profile as well**, following the instructions in [Post-Installation](#post-installation).

## What the Controller Profile Changes

Switching to the controller profile will automatically:

* Enable several mods that add controller support.
* Enable patches for various UI elements designed for controller use.
* Disable mods that conflict with controller support.
* Disable mods that can cause crashes when using a controller.
* Disable mods that do not function correctly with a controller.

You should not manually reproduce these changes. Simply switch to the controller profile.

---

# Optional Features & Customization

A Painted World includes several optional configuration choices.

## Ultrawide Support

21:9 ultrawide support is available under the:

**ULTRAWIDE OPTIONALS (21x9)**

section of Mod Organizer 2.

Enable the appropriate options if you use a supported ultrawide display.

## Leveling Options

By default, skills do **not** increase by using them.

Instead, you receive skill points that can be distributed when leveling up.

### Vanilla-Style Skill Leveling

If you want skills to increase through use again, disable:

**Oblivion XP Update**

### Remastered Leveling

If you want to use the leveling system from the Remaster, enable:

**Remastered Leveling**

Otherwise, leveling will work like vanilla.

## Food and Drink Quotes

**Food and Drink Quotes** adds humorous voice lines for your character when eating or drinking food, potions, or ingredients.

This is completely optional and can safely be disabled in Mod Organizer 2.

## Adding Your Own Mods

You are free to customize the list, but doing so comes with an important caveat:

**If you add mods yourself or change major game functions through the in-game mods menu or INI files, you will void all official support for the modlist.**

---

# Frequently Asked Questions

For common questions and solutions, see the dedicated [FAQ](https://github.com/sasquatch678/A-Painted-World/blob/main/FAQ.md).

---

# Gameplay Changes

A Painted World plays very differently from vanilla Oblivion.

The modlist introduces substantial changes to combat, magic, progression, quests, crafting, exploration, and many other systems.

For a detailed overview of the new mechanics and systems, see the [Gameplay](https://github.com/sasquatch678/A-Painted-World/tree/main/Gameplay.md) documentation.

---

# Known Issues

Even with extensive testing, some issues are inherent to Oblivion's engine or arise from the interaction between a large number of mods.

The following are known issues and recommendations.

## 1. Stuttering & FPS Drops

The game can stutter or experience significant FPS drops in certain areas, even on powerful systems.

Oblivion is an old game running on a 32-bit engine. There are fundamental limitations to what can be done to improve performance, and I have done and continue to do what I can to mitigate these issues.

### NPC-Heavy Areas

Areas containing large numbers of NPCs can be particularly demanding.

### Torches & Light Spells

Torches and light spells can cause severe FPS drops.

Unfortunately, these problems are largely limitations of the engine and can be made worse by mods that add additional objects and detail to the landscape.

There is no reliable fix for these situations.

In particularly demanding areas, avoiding additional dynamic lights may be necessary.

### Hardware-Specific Performance Problems

Certain hardware configurations can experience unexpected performance issues with an older game like Oblivion.

AMD graphics cards may be particularly affected.

If you are experiencing unusually poor performance, try the following:

1. Open `Oblivion.ini` in the `profiles` folder.
2. Set the game to **fullscreen**.
3. Open:

   ```text
   mods/A Painted World Configs/OBSE/plugins/Oblivion Display Tweaks.ini
   ```
4. Disable **borderless mode**.

## 2. Reloading Saves Without Restarting the Game

There are various issues that can occur when reloading saves from within the game or exiting to the main menu and loading a save from there.

Certain scripts may fail to initialize correctly unless the game is launched fresh. This can cause a variety of unexpected problems.

The alternate death mod exists to mitigate these problems as much as possible.

### Recommended Practice

For the most stable and bug-free experience:

**Completely close and restart the game whenever loading a save or starting a new game.**

Do not rely on returning to the main menu and loading from there.

## 3. DXVK

DXVK can occasionally cause:

* Visual anomalies
* Random crashes

If your performance is good enough without DXVK, you may want to keep it disabled.

However, DXVK provides a significant performance improvement on most systems, particularly in performance-intensive areas.

It is also currently required to use ReShade with Oblivion Reloaded Combined.

**If you disable DXVK, ReShade will not work.**

---

# Reporting Issues

A modlist of this scope inevitably contains situations that cannot all be anticipated.

Even thousands of hours of testing cannot account for every possible combination of hardware, settings, quests, mods, and player behavior. One of the fundamental principles of QA is that no single person can find every bug in a piece of software.

If you encounter an issue that:

* Is not caused by an installation error,
* Is not covered by the known issues above, and
* Does not have an existing solution,

please report it in the **Discord**.

When reporting an issue, provide as much information as possible, including:

* What happened
* What you were doing when it happened
* Where it happened
* What you were doing immediately beforehand
* Whether the problem can be reproduced
* Any relevant error messages or crash information

The more information you provide, the easier it will be to investigate the problem.

---

# Updating A Painted World

Before updating, always:

1. Check the changelog for the version you are installing.
2. Back up your saves.
3. Check whether the update requires a new game.

Some updates may not be compatible with existing saves.

## Updating Through Wabbajack

Updating is essentially the same process as installing the list.

Make sure your installation and download paths are the same as they were previously.

When prompted, select:

**Overwrite existing modlist**

You may also need to reset your resolution in the `Oblivion.ini` located in the profiles folder.

### Custom Mods

Any mods you have added yourself will be deleted when updating unless they are prefixed with:

```text
[NoDelete]
```

If you have made your own additions or modifications, make sure you understand this before updating.

---

# Removing A Painted World

To uninstall A Painted World, simply delete the modlist's installation folder.

There is no separate uninstaller required.

---

# Credits & Thanks

* **YOU**, for reading this.
* **biggie_boss**, for answering all my questions, motivating me to create APW, and introducing me to Wabbajack through his YouTube content.
* **Everyone in the Discord**, for reporting issues and providing feedback. The list would not be in its current state without you.
* **Halgari and everyone on the Wabbajack Team**, for creating and maintaining an amazing tool.

---
