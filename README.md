![banner image](https://raw.githubusercontent.com/sasquatch678/A-Painted-World/refs/heads/main/images/Oblivion%202025-09-04%2018-41-26%20-%20Copy.webp)

***

<p align="center">
<strong>An Oblivion Wabbajack Modlist by Sasquatch</strong>
</p>

<p align="center">
<table>
<td><a href="https://github.com/wabbajack-tools/wabbajack/releases">Wabbajack</a></td>
<td><a href="https://loadorderlibrary.com/lists/a-painted-world-2">Load Order Library</a></td>
<td><a href="https://discord.gg/dGP9Vy7QMG">Discord</a></td>
<td><a href="https://www.nexusmods.com/games/oblivion/collections/zznpcp">Nexus</a></td>
<td><a href="https://ko-fi.com/sasquatch678">Ko-Fi</a></td>
</table>
</p>

[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]
[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

***

# OVERVIEW

**A Painted World** is a complete overhaul of *The Elder Scrolls IV: Oblivion* focusing on:

- Stylized, timeless visuals  
- Modernized combat systems  
- Deepened RPG mechanics  
- Meaningful progression  
- Expanded cities and quests  
- New lands including Elsweyr  
- Immersive survival and roleplay systems  

Additional systems include:
- Crafting  
- Animal taming  
- Fishing  
- Housing and decoration  
- Survival mechanics and exploration systems  

---

### WORLD DESIGN PHILOSOPHY

Cyrodiil is no longer centered around the player.

From the moment you begin, you are vulnerable. Many enemies are stronger than you, and early combat often requires retreat, preparation, and planning. Exploration is dangerous but highly rewarding.

Progression is earned through:
- Preparation  
- Smart decision-making  
- Equipment upgrades  
- Environmental buffs (food, alcohol, shrines, doomstones)  

Death is frequent early on—but mastery is rewarding.

---

### DISCLAIMER

- Only **English Steam GOTY Deluxe** is supported  
- GOG and other languages are **not supported**  
- Windows 10/11 required (21H2+)  
- LTSC / modified Windows builds are **not supported**  
- HDD installation is **strongly discouraged**  

---

## SYSTEM REQUIREMENTS

| Component | Recommended |
|----------|------------|
| CPU | Quad-core Intel / AMD |
| RAM | 4 GB DDR4 |
| Storage | SATA SSD or better |
| GPU | DX9.0c + Vulkan compatible, 8GB VRAM |

**Storage required:** ~115 GB

---

## INSTALLATION

### PRE-INSTALLATION

1. Install:
   - Visual C++ x64  
   - .NET Runtime 8 Desktop x64  
2. Fully uninstall Oblivion (including Documents folder)  
3. Disable OneDrive and file sync tools  
4. Install Oblivion outside Program Files (e.g. `C:\Games`)  
5. Launch once and exit  
6. Apply 4GB patch to `Oblivion.exe`  
7. Disable antivirus or add exclusions  
8. Disable overlays (Steam / Nvidia / Discord)  
9. Cap FPS to 60  

---

### WABBAJACK INSTALLATION

1. Download Wabbajack  
2. Place in safe folder (e.g. `C:\Games\Wabbajack`)  
3. Open Wabbajack → Browse Modlists  
4. Select **A Painted World**  
5. Set install path (e.g. `C:\APW`)  
6. Press install and wait  

---

### INSTALL ISSUES

- Missing Oblivion.exe → 4GB patch not applied  
- Whitelist errors → wait for update  
- Game not found → incorrect install location  
- Antivirus errors → add exclusions  

---

## POST INSTALLATION

### RESOLUTION FIX

Edit: profiles/A Painted World/Oblivion.ini

Match:
- iSize W  
- iSize H  

to your monitor resolution.

---

### ANTIVIRUS EXCEPTION

Required for stable operation. Add modlist folder to exclusions.

---

### RESHADE (OPTIONAL)

- Install from reshade.me  
- Target `Oblivion.exe` (Stock Game folder)  
- Select Vulkan  
- Effects already included via MO2 preset  

---

## STARTING THE GAME

Launch via `ModOrganizer.exe`

- Select **Oblivion profile**
- Press Run

You will begin in a ship cabin:
- Create character  
- Loot starting supplies  
- Use passport to adjust choices  
- Sleep to finalize start location  

World progression begins immediately after.

---

## CONTROLLER SUPPORT

Switch MO2 profile:
- “A Painted World - Controller”

Enables:
- Controller UI patches  
- Input remapping  
- Disabled conflicting mods  

---

## OPTIONAL FEATURES

### Ultrawide Support
Enable under “ULTRAWIDE OPTIONALS (21x9)”

### Leveling Systems
- Oblivion XP → skill-based leveling  
- Remastered Leveling → APW system  
- Vanilla leveling also supported  

### Extras
- Food & Drink voice quotes (toggleable)  

---

## SUPPORT POLICY

Modlist is heavily integrated:
- External edits may break stability  
- In-game mod menu changes unsupported  

---

## FAQ

See:  
https://github.com/sasquatch678/A-Painted-World/blob/main/FAQ.md  

---

## GAMEPLAY OVERVIEW

See:
https://github.com/sasquatch678/A-Painted-World/tree/main/Gameplay.md  

---

## STOCK GAME / ROOT BUILDER

- Uses Stock Game isolation system  
- Keeps base Oblivion clean  
- Uses Root Builder for ENB / ReShade / hooks  

---

## KNOWN ISSUES

- Performance drops in dense NPC areas (engine limitation)  
- Save reloading may break scripts  
- Certain perks can bug on quickload  
- DXVK may cause visual anomalies  

Restart game for best stability.

---

## UPDATING

- Backup saves recommended  
- Overwrites existing installation  
- May require new game after major updates  
- Custom mods without `[NoDelete]` will be removed  

---

## REMOVAL

Delete folder to uninstall.

---

## CREDITS

- YOU, for reading this  
- Wabbajack team  
- Discord community testers  
- Biggie_Boss for guidance and inspiration  
