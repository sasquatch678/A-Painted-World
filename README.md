# A Painted World - Oblivion Wabbajack Modlist

![banner image](https://github.com/sasquatch678/A-Painted-World/blob/main/cover_16x9.png)

Oblivion Wabbajack Modlist by Sasquatch.

<table stlyle="border: none;">
<tr>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Download on Wabbajack</a></td>	
<td><a href="https://loadorderlibrary.com/lists/a-painted-world-2">Load Order Library</a></td>
<td><a href="https://discord.gg/Tb5ETzBYjd"><img alt="Discord" src="https://cdn.logojoy.com/wp-content/uploads/20210422095037/discord-mascot.png" width="64px" ></a></td>
</tr>
</table>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Overview

**A Painted World** is a complete overhaul of TES IV: Oblivion with a focus on stylized and timeless visuals, modernized combat, deeper rpg mechanics, and meaningful progression. It features expanded cities, additional quests, a more refined leveling system, more unique and detailed landscapes, and new lands such as Elsweyr. It is heavily focused on immersion and progression, and additionally has many slice of life features such as crafting, animal taming, fishing, home building/decorating, and more.

You must be prepared to cast aside your previous notions about Cyrodiil. The world no longer revolves around you, the player. Do not expect to be able to beat every monster or NPC you meet from level one. Previously familiar areas may now be much more dangerous and you will be forced to retreat from enemies who are too powerful to beat until you are stronger. You will probably die a lot more often now. However, if you have the ingenuity, skill, and luck to survive the odds stacked against you then you will be justly rewarded for your bravery!

If you feel overwhelmed by the difficulty when you first start out in this dangerous new world, do not be discouraged. Be cautious at first. Upgrade your gear as often as possible. If you find yourself facing overwhelming odds, run away and return later when you are more powerful to reap revenge on your foes. If necessary, seek help from the guards and legion patrols along the roads. The farther you venture from civilization, the deadlier enemies you will come across, and the greater the rewards. With every level you will become stronger than before. Don't give up!


### Disclaimer

Owing to the need to clean master files and certain errors with Wabbajack, A Painted World only supports **English Steam** versions of Oblivion GOTY Deluxe edition. 
**GOG and other Languages are not supported**.

Only Windows 10 and 11 work with Wabbajack fully. LTSC, special variants, lightened editions or any other modified variant **WILL NOT WORK**. Your windows version **must be 21H2 or newer** to run both Wabbajack and A Painted World.

Running the list from Hard Disk Drives or external drives is **STRONGLY ADVISED AGAINST**. A lot of content is swapped at game run time and, as a result, fast storage and RAM are needed.

### Recommended System Requirements

If you can run vanilla Skyrim, you should be able to run APW without issue.

| Component    | Recommended | 
|:--------------:|:-------------:|
| CPU | Quad-core Intel or AMD CPU
| Ram | 4GB DDR4 Ram
| Storage | SATA SSD or higher
| GPU | Direct X 9.0c and Vulkan compliant video card with 6gb of VRAM

Space required: ~120GB Total 

## Installation

Due to being a Wabbajack list installing A Painted World is painless and easy, taking a fraction of the time it would to create a modlist like this yourself. You will need to own a Steam copy of Oblivion GOTY Deluxe Edition before proceeding.

### Pre-Installation

The following steps are required to be completed before downloading A Painted World.

1. Install [Visual C++ x64](https://aka.ms/vs/17/release/vc_redist.x64.exe) & [.Net Runtime v5 desktop x64](https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-8.0.5-windows-x64-installer)
3. Fully uninstall Oblivion by deleting the folder and the Oblivion folder inside \Documents\My Games\.
4. Fully disable OneDrive and any other programs which hook into user file areas.
5. Reinstall Oblivion into a location that is not Program files. Somewhere like `C:\Games` is a good location. Avoid long file paths. If you only have one drive, look into LostDragonist's [SteamLibrary tool](https://github.com/LostDragonist/steam-library-setup-tool/wiki/Usage-Guide).
6. Start the game once and let it do the graphics check. Do not worry about the settings as it will be replaced during installation.
7. Navigate to Documents\My Games\Oblivion and open RendererInfo.txt in a text editor.
   On the last line you should see ```Shader Package         : 19``` If this does not say 19 for you, change it so that it does. Close and save the file, then right click it and select Properties. Make a checkmark on Read-only.
8. Download and extract the 4gb patch from the link here. Run the exe on the Oblivion.exe in your game folder. <https://www.nexusmods.com/oblivion/mods/45576?tab=files>
9. Download and install the basic version of the codecs pack here. This is important for audio to play correctly and can cause crashes if it is missing. You don't need to select anything in particular, the default options are fine. <https://www.codecguide.com/download_kl.htm>
10. Remove/Disable any 3rd party antivirus such as MalwareBytes or Webroot. These **will** mess with the installation and, in the case of the latter, causes more problems than it solves.

***

### Wabbajack Installation

#### Installing Wabbajack

Once you have completed pre-installation, download the [latest version of Wabbajack]((https://github.com/wabbajack-tools/wabbajack/releases)) and place it in a folder such as `C:\Games\Wabbajack`. Do not place it in program files, on your desktop or in your downloads folder. I recommend placing it on an SSD as it will work quicker on there.

:warning: **NOTE**: A Painted World will **always** require the latest version of Wabbajack **UNLESS IT IS SPECIFICALLY STATED HERE**. :warning:

***

#### Downloading and Installing A Painted World

Downloading and installing the list can take a while depending on your internet connection and computer. To install A Painted World, complete the following steps.

1. Open Wabbajack and click on browse modlists.
2. Press the download button on A Painted World and wait for it to download.
3. Set the installation folder to be somewhere like C:\APW. **Do not install it to your desktop or downloads folder.**
4. The download location does not need to be on a SSD but it makes installing a bit faster.
5. Press the play button to begin.
6. Go and pet your nearest fluffy animal whilst Wabbajack does its thing. Alternatively read through this readme again.
7. If the installation is successful, jump for joy and move onto [post installation](#post-installation). If the installation is unsuccessful, follow what is below.

***

#### Problems with installation

It is possible that you may encounter an error with Wabbajack when installing. Some common issues are listed below.

- Failed Downloads
	
	- Missing Manual Downloads: Oblivion.exe - You did not apply the 4gb patch. Go back to [Pre-Installation](#pre-installation)  and read thoroughly.
	
	- If you get a failed downloads error in wabbajack from these mods, please download from the links below and manually move them to the downloads folder of the modlist, then rerun wabbajack.

   Fire Retexture 1k 1.2
   https://www.mediafire.com/download/ctd689d2etnlabw/fire+retexture+1k+1.2.rar

- x is not a whitelisted download:

	 - This will happen when I update the modlist. Please check if there is a new update or wait until you see a release ping.

- Wabbajack could not find my game folder:

	- Either buy the game or go back to the [Pre-Installation](#pre-installation) step.

- Antivirus reports a virus:
	- You did not follow the steps in [Pre-Installation](#pre-installation). Go back and follow it.
	- If you have followed it then you can fix this by [adding an exclusion for Mod Organizer in Windows Defender](https://www.thewindowsclub.com/exclude-a-folder-from-windows-security-scan).

## Post-Installation

### Frequently Asked Questions

Please consult the  [FAQ](https://github.com/sasquatch678/A-Painted-World/blob/main/FAQ.md) page here to see if your question is already answered.

### Gameplay Changes

A Painted World plays very differently from vanilla Oblivion, please review [Gameplay](https://github.com/sasquatch678/A-Painted-World/tree/main/Gameplay.md) for a summary of some of the new mechanics.

### Stock Game & Root Builder

A Painted World utilizes a Wabbajack technology called Stock Game. What this essentially does is create a copy of your Oblivion installation within the installation location of the list. This enables greater compatibility with other mod-lists and keeps your original game folder clean of any outside files.

A Painted World also utilizes Root Builder alongside Stock Game to enable easier management of hooks such as ENB, Reshade and other mods which would ordinarily require being installed to the game folder. Please see this guide to [Root Builder](https://github.com/The-Animonculory/Modding-Resources/blob/main/Root%20Builder%20for%20Skyrim%20AE.md) for more details.
***

### Starting up the list
Open the installation folder and double-click on the program called `ModOrganizer.exe`. 

Make sure the dropdown box on the right is set to `Oblivion` and press the `Run` button.

### Controller Support

Copy and paste the following link to a web browser. Hit enter.

steam://controllerconfig/22330/3299476272

A prompt will appear to open it with Steam, select Open Link. An image of the layout will appear, use :stop_button: or X to import the layout. From here you can launch the list normally through MO2 and use the controller to play. 

### Optional Mods - Ultrawide Support & Performance

A Painted World comes with several customization options. 

There is 21x9 ultrawide support under the "ULTRAWIDE OPTIONALS (21x9)" section of Mod Organizer 2. 

By default skills do not increase by using them and instead you get skill points you can distribute when leveling up. You can choose to enable skill based leveling again.

If you need a boost in FPS, you can choose to enable the Performance LODs.

If you add any mods yourself or change major game functions through the ingame mods menu or ini files you will void all official support for the modlist.

## Known Issues
1. The game can stutter or fps can drop quite heavily in certain areas. Oblivion is an old game on a 32bit engine, I have done and am still doing what I can to alleviate this as much as possible. Elsewyr cities in particular tank fps. Torches and light spells can cause fps to dip very heavily ias well. This is unfortunately just an engine limitation which gets exasperated by some of the mods adding more objects and detail to the landscape. There is no real solution except to avoid using lights in these areas at night.

## Updating the modlist

Before updating, please check the changelog and back up your saves. You may need to start a new game after certain updates.

Updating is like installing the list. Simply make sure your paths are the same and tick the `overwrite existing modlist` button. **Note**: Any mods you have added will be deleted when updating.

## Removing the Modlist
Simply delete the folder, and you have uninstalled it.

## Credits and Thanks

- _YOU_ for reading this.
- biggie_boss for answering all my questions, motivating me to create APW, and introducing me to Wabbajack in the first place with his Youtube content.
- everyone in the Discord making reports and providing feedback. The list would not be in the current state without you.
- Halgari and everyone on the WJ Team - Wabbajack is an amazing tool.

