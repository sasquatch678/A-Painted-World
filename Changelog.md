## **2.1.7**

**Added**
- Harvest Containers (only the meshes, since OOO decided to remove them without updating the file paths for all containers)

**Changes**
- increased all weapon damage by 15% (enemies and player)
- buffed the starting mysticism spell weak vitae siphon to absorb 6 points of health over 2 seconds (was just 6 points per cast)

**Bugfixes**
- fixed bug that could cause attribute and skill points to not be saved on levelup

## **2.1.6**

**Updated**
- SB Arrow Master
- Maskar's Oblivion Overhaul

**Changes**
- renamed "Hell Hound" from OOO to "Kynhound" to better fit the setting
- disabled key to toggle status bars for needs
- the slaughterfish chowder recipe now requires corn instead of scales
- reworked altar/wayshrine buffs, will no longer cure disease, restore health, or restore attributes. however, the pilgrim npcs added by OOO near each wayshrine will now offer healing, cure disease, and restoration services from Oblivifall - Losing My Religion
- tamed pets are no longer essential
- reduced npc per level health mult to 2x (was 3x)
- reduced exploration xp by 33%
- slightly reduced reading xp (books that gave 25xp will now give 15xp)
- increased cap on attribute and skill points able to be spent per level-up on one attribute or skill to 10 (was 5) and up to 15 for skills (was 5). The intention is to create more interesting choices (do I put all my points into one thing, or diversify a bit?) rather than just slowly level up the same few things at once.
- increased skill points rewarded on level up to 50 (was 35), however the amount of points required to increase a skill by 1 will now increase by 1 each time it reaches a new level of skill mastery (ie. a journeyman skill would cost 1 extra point compared to apprentice, an expert skill would cost 2 extra points, and master 3). The intention is to get builds going a bit sooner and allow a baseline level of proficiency in more skills but still require longterm commitment to truly master a skill.
- nerfed damage and increased magicka cost of flame atronach fire balls

**Bugfixes**
- fixed nude Mythic Dawn Leader


## **2.1.5**

**Updated**
- SB - Arrow Master
- Simple Inheritance

**Changes**
- updated dremora seducer appearance and race description
- reduced sprint fatigue cost to 15 (was 20)
- improved underwater visibility
- reduced minimum amount of athletics skill needed to avoid light attack penalty to 25 (was 50) and reworked the formula to determine the minimum amount to no longer have a base value, but instead scale more with weapon weight (0.35 * weight, was 10 + 0.15*weight)
- increased power attack delay timer to 0.175 (was 0.125) to avoid instances triggering a power attack when you didn't intend to

**Bugfixes**
- fixed missing pond in the Arboretum
- added block in combat script to re-enable left click if the player enters a menu, while keeping it disabled if the menu is a crafting menu to prevent withdrawing infinite crafted items with no material cost

## **2.1.4**

**Added**
- Simple Inheritance

**Changes**
- slightly modified detection settings - goal is to improve performance in areas with many actors and decrease chances of aggroing an entire cell
- reduced attributes awarded on levelup when oblivion xp is disabled to 10 (was 12)
- disabled lod shadows, noticeable performance improvement in cities and exteriors
- buffed the altmer researchers in Belda

**Bugfixes**
- fixed missing desk mesh
- fixed being unable to enter correct arena for infinitum compendium quests
- fixed ayleid well light and sound not disappearing when activated
- fixed landscape tear near rimmen

## **2.1.3**

**Added**
- Combat Additions (only the optional animation files, third person only)

**Updated**
- SB - Arrow Master
- Oscuro's Oblivion Overhaul Updated
- OOO Enhanced

**Changes**
- reduced amount of food loss per hour to 5 (was 30)
- reduced well fed threshold to 50 (was 60)
- reduced power attack delay to 0.125 seconds (was 0.250)
- looting coffins no longer gives you a point of infamy

**Bugfixes**
- greatly reduced the amount of lightbulbs in the bloodworks as this could cause a rare crash when re-entering after an arena match
- the Frostcrag region can no longer have weather from the Shivering Isles
- fixed typo in Blunt master perk description
- fixed infinite summon limit
- fixed grey seam on some female clothing that showed skin

## **2.1.2**

**Added**
- Diverse Liches (Modders Resource)
- OOO Enhanced Better Dungeons Patch
- Menu Controls Modernized

**Removed**
- Supreme Magicka - Levitation Cloud Fix
- Customizable Magic Progression - redundant with changes to Supreme Magicka ini
- QZ Easy Menus Update - redundant with Menu Controls Modernized
- Loot Feed

**Changes**
- disabled Bloodmoon weather change
- moved the Cyrodiil Transportation NPC at the Bravil, Anvil, and IC docks and disabled their boats to save draw calls in these areas
- disabled clutter/nature across from the Bravil docks to reduce draw calls in the area
- disabled a handful of lights in the exterior of Miscarcand to improve fps in the area
- disabled a handful of lights in Leyawiin Castle to improve fps in the cell
- Crazed and Mystical imps now just drop regular imp gall instead of crazed/mystical imp gall to cut down on the amount of random clutter items
- City topics will now only appear for npcs who live in that city
- reduced exploration xp by 25%
- disabled glowing flame effect on summoned creatures from supreme magicka
- enabled skill xp progression in Supreme Magicka, this will also make spamming spells out of combat to power level less effective than using in combat (only has an effect when oblivion xp is disabled)

**Bugfixes**
- disabled amazons and bandits residing in the mines overhauled by Productive Mines so they would stop murdering the miners
- lowered an Ayleid altar outside Trumbe and a chest inside to no longer be floating
- bears can no longer cause diseases, to prevent a rare crash
- reverted bound armor appearance to that of vanilla as ooo enhanced replaces it with missing resources
- fixed some cloaks hiding your characters hair

## **2.1.1**

**Added**
- Status Bars for Needs - Vanilla and Darn Retexture
- Extended UI - Vanilla and Darn Boss Bar Retexture

**Changes**
- heavily reworked OblivionXP settings and it is now enabled by default - the curve scales much more evenly and is much lower overall at higher levels. Quests reward much more xp compared to anything else.
- renamed "Thugs" from MOO to "Bandits" and "Looters" to "Marauders" to avoid inconsistencies with dialogue, quests, and level design from other mods
- removed "The Luggage" system from Cobl
- disabled all of the fake chalice's from that one mages guild quest
- moved levelup icon to be beside the compass

**Bugfixes**
- fixed broken Mages Guild Pupil robe mesh
- fixed player controls staying disabled after mankar camoran finishes his speech
- reverted changes to the fighters guild Witchcraft quest from a few updates ago - if you get lost in the labyrinth, you can now follow the trail of lights for a guaranteed pathway through. added a quest stage to explain what happened and to suggest following the lights.

## **2.1.0**

**Added**
- Performance Sound
- Combat Stance Reanimation - a custom preset
- Mysticism Auto Recharges Weapons
- Maskar's Unarmored Skill
- Magicka based enchantment limits
- Supreme Magicka Update
- Simple Horse Utilities

**Updated**
- Better Cities

**Removed**
- MoreHeap
- Fundament
- PSO - Pickpocket Skill Overhaul
- FEA - Fundament Enchanting Addons
- Alex's Simple Mark and Recall Spells - redundant with Supreme Magicka
- Fleshed out Necromancers - redundant with Supreme Magicka
- Horse Gameplay Overhaul
- Retexture Diverse Female Faces for OCOv2 - And some cleaning to the others

**Changes**
- downsides to shields now only buffs the player when they aren't using a shield, there is no more penalty to having a shield equipped
- changed Lord sign passive to 75 points of fortify health instead of % regen as I believe the script that controlled the regen could cause crashes. also reduced weakness to fire to 25% (was 50%)
- The Shadow lesser power now also grant telekinesis, which has many new applications thanks to Supreme Magicka
- removed intelligence and willpower requirement from progressing in the mages guild as this was never an intended requirement
- re-enabled heap mode in ORC
- changed the rock texture used in the cliffs of anvil to use a beach rock texture instead of the jerral mountain rock texture so there aren't snow covered rocks on the beach
- removed init message from AV Uncapper
- removed diminishing returns on various magic effects since most of them are already hard capped to a certain value, also may solve some crashes with creatures that have 0 magicka applying diseases
- removed some lights in the chorrol chapel of stendarr to improve performance in the cell
- added new and reworded existing loading screens to explain some of the new magic mechanics ingame
- improved fps in Leyawiin substantially by removing clutter objects placed outside the walls
- pawnbrokers and general traders may now sell paint mixing bowls, blank canvases, and easels which act as supplies and a crafting station to make paintings
- added over 100 new crafting recipes for furniture and decorations - furniture can be crafted at a workbench, and carpets and tapestries at loom stations
- changed position of weapon and spell icon on hud to match the hand used in animations
- removed the imperial furniture store, since the majority of the items can now be crafted
- absorb effects are now part of the mysticism school, as in morrowind
- replaced Great Helm model used on guards with the Plate Helmet model from OOO Enhanced

**Bugfixes**
- disabled LODCut in ORC as this could cause stutters and visual bugs
- fixed floating ayleid castle east of Anvil
- fixed an oblivion gate rock east of anvil that would appear regardless if that oblivion gate was active or not
- fixed fletching jig appearing in leveled loot
- removed tinkering kit recipe
- consistency patched all NPCs (again) to make use of the update from OOO Enhanced - new gear should appear more often now
- fixed water having no transparency near shoreline (set bUseWaterDepth=1 in oblivion.ini)

## **2.0.14**

**Changes**
- reworked many lore dialogue options, making the conditions more strict so that when they appear they are always relevant to that specific npc, and rewording the topics to not get in the way of actual important ones
- the fighters guild members that appear during the Blackwood Company questline will now wear the fighters guild uniform and not random leveled armor
- various shader/visual improvements
- made culling settings stricter inside cities to improve performance
- slightly improved performance in some interiors by adjusting shadow point light settings

**Bugfixes**
- fixed yellow/green flame effects
- fixed missing meshes in sleepy creek village
- fixed numerous issues with missing dialogue, stuck quest progress, crashes, and conflicts with other mods during the Blackwood Company questline

## **2.0.13**

**Updated**
- Maskar's Oblivion Overhaul
- OOO Enhanced

**Changes**
- replaced ORC's heap settings with MoreHeap as it appears to be more stable
- replaced the "nix-hounds" in Caldera with durzogs from MOO - no more green skinned wolves

**Bugfixes**
- fixed arena having a black skybox

## **2.0.12**

**Updated**
- ORC to 3.1.1

**Bugfixes**
- fixed bug which could cause Highwayman to spawn with infinite health if the player was below level 5

## **2.0.11**

**Updated**
- ORC to 3.1
- Join the Order of the Black Worm

**Removed**
- Emmett LaFave Oblivion Inspired Music

**Changes**
- disabled Skaal Werewolf hunters from spawning as scripts associated with this faction could cause the game to crash

**Bugfixes**
- fixed weird yellow reflections in Blackwood
- fixed lighting in temple of the one

## **2.0.10**

**Added**
- High Fantasy Cyrodiil Caves
- Join the Order of the Black Worm Voices (ElevenLabs)
- Water 17
- Emmett LaFave Oblivion Inspired Music

**Updated**
- Glowing Nirnroot

**Removed**
- 2020 Retexture Project - Caves
- Retextured Caves and Mines Doors

**Changes**
- enabled dynamic window reflections
- disabled ORC water & underwater shader (so many bugs)
- reworked the quest "Witchcraft" in the Fighters Guild. The witch can no longer banish you to the labyrinth, and is a straightforward kill and collect quest with a reasonable amount of hp. Also gave her a new more witchy outfit instead of generic robes.
- Glenmoril witches will now wear the "Shaman Robe" from OOO Enhanced instead of generic lower class clothing

**Bugfixes**
- fixed Anvil towers lod mesh using towers from Cheydinhal
- removed animated sparkle from gems and nuggets to avoid ambient occlusion issues with OR
- removed duplicate weapons from some skeleton enemies

## **2.0.9**

**Added**
- WalkBlessed
- katkat TW3 Bears
- Ayleid Ruins Fixed - Mesh Replacer and Modder Resource - when did I even remove this?

**Removed**
- No Inventory On Alt-Tab

**Changes**
- improved shader visuals
- improved some weapon enchantment visuals to be less bulky
- recolored goblin skin to be more green and less yellow
- recolored orcs to be more green and less grey/brown
- recolored argonians to be more red and less orange/yellow
- recolored storm atronachs to be blue instead of orange
- desaturated textures from rainbow argonians
- adjusted lighting in the starting cell so you can better see character eyes

**Bugfixes**
- tweaked sneak settings so player won't aggro an entire cell as easily
- disabled first person body in ORC
- set CSHook = 0 in ORC - maybe more stable?
- edited some dialogue conditions referring to kvatch and the emperor's assassination so they can only occur when the player starts the mq

## **2.0.8**

**Added**
- Enhanced Vegetation - Darker trunks
- Race Balancing Project - just textures and meshes
- Welkynd and Varla Stones Glow
- Nirnroot Glows
- Doomstones Glow
- Ayleid Wells Glow

**Removed**
- Custom Enhanced Camera - redundant with ORC 3.0, buggy
- Additional OR Effects - incompatible with ORC 3.0
- Better Underwater and Night eye shader for OR - incompatible with ORC 3.0
- WalkBlessed - incompatible with ORC 3.0
- OOO Extended - buggy and outdated, most features have been replaced by OOO Enhanced
- Glowing Wonders

**Updated**
- Crash Logger Improved
- Oblivion Reloaded Combined

**Changes**
- added basic fishing rod and fishing guide to common clutter leveled lists
- the ability of ayleid wells to restore health and magicka will now reset once per day even if the player has already collected the one time magicka buff, primarily for atronach players
- cloaks now give frost resistance instead of frost shield
- improved Oblivion realm visuals

**Bugfixes**
- restored OOO wildlife decisions script
- fixed crash which could occur east of anvil approaching the wayshrine of akatosh caused by corrupt pathgrid


## **2.0.7**

**Added**
- Redguardians
- Replacers for Redguardians and Better Looking Redguards
- Retexture Diverse Female Faces for OCOv2

**Removed**
- Waterfalls replacer
- Remade Vanilla Male Undergarments
- OCO Face Updater
- Oblivion Stutter Removed, re-enabled ORC heap mode - needs more testing

**Changes**
- actors may no longer flee from combat on low hp as this is potentially causing crashes
- actors may no longer follow the player through doors as this is potentially causing crashes

**Bugfixes**
- made Contingency (Mage's Brilliance) trigger more reliably and also fixed an issue that allowed the stored spell effect to stack per enemy that entered combat with the player
- fixed argonians not using the tail and claws from enhanced beast races
- cleaned up some clipping at the temple of the ancestor moths
- cleaned a dozen various plugins to convert deleted records into disabled
- potentially fixed Av Latta Magicka crash when trying to remove a stuck scripted effect on a deleted activator
- fixed magical stones missing lods

## **2.0.6**

**Added**
- Magic Magnitude Multipliers
- Customizable Magic Progression
- Night Sky Fire and Ice
- Oblivion Stutter Remover - replaced the heap mode from ORC as in testing it appears to be more stable

**Removed**
- Decorator Assistant - redundant and can cause crashes with Enhanced Grabbing
- Let People Speak - causes crashes
- Ragdolls for Oblivion - pretty sure this can cause crashes
- Channeling Staves - redundant
- Glowing Plants & Mushrooms
- Best Combined Night Sky

**Changes**
- Intelligence will now also scale spellcasting magnitude by a percentage. Attribute description adjusted accordingly. You can view the amount in the misc stats screen.
- Willpower will now also scale magic resistance (or weakness if below 25) by a percentage. Attribute description adjusted accordingly. You can view the amount in the misc stats screen.
- Spell magnitude is now increased by 10% when wielding any staff, and decreased by 10% when wielding a weapon or shield. There is no penalty or bonus when empty handed.
- made speed or agility slightly more important when calculating attack speed
- Hoarfrost Castle quest will now only start if the player is in Chorrol or Bruma, or if the player visits the castle
- Highwood quest will now only start if the player is in Anvil or if the player visits the farm
- nerfed essential death time from 60 to 15 seconds so you don't have to wait around if an essential quest npc goes down
- readded old snow texture, edited snowy rock textures to blend better
- renamed "tunic of the dead" and "hood of the dead" to "necromancer robe" and "necromancer hood" since that is their base form and so it is more clear that's what you're meant to turn in at the necromancer robes box in the mages guild
- can no longer close menus with space to allow using a space in naming custom enchanted items. now can use esc in addition to right click
- buffed the infinitum compendium mages guild beast research boss to a minimum level of 15 instead of 1

**Bugfixes**
- silver veins no longer can drop platinum and gold veins can no longer drop copper
- fixed bug preventing you from closing the inventory menu
- removed follow dialogue from random nameless mages guild npcs
- fixed remaining lighting/fog issues in cells that I missed after removing All Natural in 2.0.4 (mostly Oblivion Gate interiors)

## **2.0.5**

**Added**
- Tales from Elsweyr Anequina Rev's Redo
- Tales from Elsweyr Anequina Rev's Redo Voiced
- Tales from Elsweyr Anequina Rev's Redo FIXED
- 2020 Retexture Project - Trees and Shrubs - Handpicked

**Removed**
- Tales from Elsweyr Anequina
- Lush and Gaudy Demonic Frippery

**Updated**
- OOO Enhanced

**Changes**
- general shader visual improvements
- buffed secondary damage magicka and fatigue effects of elemental spells 4x. added extra second to fire burn duration
- nerfed damage from elemental weapon spells by ~20%, increased base spellmaking cost 1.45 -> 2.0
- nerfed enchantment damage by 30% ~ the difference between an enchanted and unenchanted weapon is extremely large, to the point most enchantments more than double your damage output. this change is intended to weaken the player in late game and allow me to move more power into the base weapon damage. it also makes non damaging enchantments more attractive since they were not touched. enchantments are still powerful, there is just less of a night and day difference.
- buffed base weapon damage by 10%
- buffed arrow damage by 25%
- marksman fatigue loss reworked. now scales 3 to 0 from novice to expert (was 5 to 0 from novice to master)
- reduced player confidence from 100 to 65 (this affects how likely enemies are to flee on low health)
- made block less op, base weapon block amount is now 50% (was 75%), hand to hand now 37.5% (was 75%), shields are now 50% more effective at blocking than no shield (was 25%), and timed block window reduced to 0.3s (was 0.5s)
- reduced power attack fatigue mult from -50 to -35
- increased moonlight brightness
- imperial legion battlemages will now wear red hoods
- imperial legion foresters outfits patched for consistency between different mods
- replaced op items in the Thieves Guild HQ - Unhealthy Competition safehouse
- nerfed speed bonus from the steed doomstone power so the camera doesn't bug out so much when using it
- dungeon traps are now significantly more deadly
- reduced draw distance settings in cities so performance should be a bit better in them
- removed excerpt on guild guides in the book "An Overview of Travel in Cyrodiil" since this method of transportation is something you unlock later through a quest reward, not as a default
- resculpted the landscape around frostcrag spire so the mountain isn't so ugly when the tower is too far to display
- kvatch sigil stone will no longer blast you with shock spells
- removed "Punished Seducers" from leveled lists
- recolored existing and added one new grass type to the gold coast

**Bugfixes**
- gave Meersmark (the dunmer vendor at the tent in the Waterfront) a new shirt so his skin seams won't be so apparent
- changed texture on the tail for Ohmes-raht so they don't have a nasty skin tail
- fixed Talos Bridge and Weye having Frostcrag location tag
- fixed steel shield in hand not matching the model for the steel shield on your back
- disabled raider boss in Arpenia so that during one of the quests for the Blackwood Company an npc won't be killed by the boss and soft lock the quest
- fixed crash which could occur when attacking a power attacking creature
- fixed crash which could occur when an npc summoned a zombie, skeleton, or bear
- fixed invisible peg leg pants
- fixed black background on anequina palm tree leaves
- fixed kotn priory mesh having purple windows
- fixed lighting in Reaper's Sprawl in the kvatch oblivion gate
- fixed bug which could cause Menien to be unable to leave his cage if the player chooses to rescue him
- fixed issues with the camp outside kvatch not moving into the city after closing the oblivion gate and starting kvatch rebuilt
- changed silver and gold nugget models to avoid ambient occlusion issues with ORC
- fixed invisible gold bars in the IC bank
- fixed landscape hole at Anvil cliffs
- fixed landscape at the Order of the Hour HQ
- fixed some inconsistencies with weather colors and lighting in different regions

## **2.0.4**

**Added**
- Better Underwater and Nighteye Shaders for Oblivion Reloaded
- Improved Fighters Guild Patches
- new snow and anvil street textures which blend much better
- BAF - Beast Argonians Forever Early Version

**Updated**
- OOO - Oscuro's Oblivion Overhaul - Updated ESPs
- OOO - Oscuro's Oblivion Overhaul - Updated (Unofficial patch)

**Removed**
- All Natural
- Interior View Distance
- Disable Detect Life During Dialogue - doesn't work with Av Latta Magicka

**Changes**
- removed particle shader from detect life and detect dead to make it less obnoxious
- maximum effectiveness of Charm spells is limited, depending on caster’s Illusion and Personality and target's Willpower
- moving while having Invisibility effect will stop natural Magicka regeneration
- nirnroot now has 100% harvest chance by default so Sinderion's quest isn't total ass

**Bugfixes**
- recentered UW hud preset
- fixed level design conflicts in Sercen between The Ayleid Steps and Ayleid Ruins Overhaul
- fixed warrior and tower powers being greater instead of lesser
- fixed some starting choices still giving 10 instead of 5 healing potions
- fixed clipping conflicts in bravil fighters guild basement
- moved enemies in Rielle so player isn't gangbanged immediately upon entering
- improved rain performance
- fixed anvil notice board clipping with stone wall
- remade city/draw distance settings, much lighter impact overall and potentially fixes excess string/save bloat

## **2.0.3**

**Added**
- Rainbow Argonians
- Remade Vanilla Male Undergarments
- AI Enhanced - Ruined Ruins

**Updated**
- Maskar's Oblivion Overhaul

**Removed**
- Improved Barter Calc Gold - redundant feature in MOO v5 and MOO does it better anyway
- Drifting Mists - poor performance and too bright to look good in most situations
- used xedit script to remove 30% of all coconut palms, they are just too numerous and also hurt performance
- Qarl's Redimized - redundant
- glowing cave mushrooms

**Changes**
- shader and visual improvements
- added new default hud configuration for normal and ultrawide
- light attacks now have a minimum fatigue requirement to use, scaled with weapon weight, that gets removed at journeyman athletics. this means you can no longer light attack until you regen over the threshold unless you have this skill level.
- enemies can turn again during light attacks, this change will make it more difficult to simply hold strafe and auto win against most enemies. power attacks are still movement restricted
- increased torch and lantern radius 2x
- imperial luck passive will now only trigger vs humanoids (aka other playable races)
- disabled guar spawns
- removed the spectral soldier in vilverin
- spell scribing key changed to C to avoid conflict with spell favorites menu
- reduced brightness of turn undead effect
- replaced the fake enchanting altar at the Warlock's Luck at the Waterfront with a real one
- removed annoying music in oblivifall cathedrals
- Knight Commander Percy from Better Cities who roams the Waterfront and Temple District will now wear a set of Kynaran Order equipment from Oblivifall
- Mazoga now wears a set of White Stallion Knight armor from Better Cities

**Bugfixes**
- fixed issue which could potentially cause purple square snow
- fixed some capes which were making people bald
- fixed gold trim on imperial palace helmet not matching the trim on the rest of the armor
- moved a terrace in Bruma to prevent z-fighting
- removed scamp in the vilverin puzzle room so the skeletons won't aggro it through the walls and stay locked on to it
- fixed jerky third person camera movement when moving diagonally/uphill and other 3rd person offset improvements
- fixed loot menu config for normal monitors so it doesn't run off the screen
- fixed crash which could occur when leaving the arena after a match
- fixed invisible Cuirass of the White Stallion, Dragonskin Cuirass, Gauntlets of Fury, and Gloves of Wrath
- fixed bug which could cause pitch black foliage in certain interiors
- fixed bug which could cause a random tumbling sound around the player
  
## **2.0.2**

**Added**
- Qarl's Redimized - only fort textures
- Enhanced Sounds Overhaul

**Changes**
- improved underwater visibility
- Luck can now be leveled just as quickly as other attributes
- reworked class specialization and skill bonuses. Magic now fortifies Intelligence, Willpower, and Personality +10, Stealth fortifies Speed, Agility, and Luck +10, and Combat fortifies Strength and Endurance +10 and adds +1 attack damage. Skill bonuses now give +5 to health/mag/fatigue instead of +10.
- reworked enemy health and player damage scaling to reduce impact of additional flat damage added to all attacks. this mechanic is included to reduce chances of enemies becoming too health spongey, but was a bit too powerful and overshadowed your base character stats. Overall should feel very similar but slightly harder to kill high level enemies at low level.
- turned off MOO level scaling, something I forgot to do when updating to v5. this means average enemy level should be lower.
- nerfed multiplier to the attacker gauntlets' armor rating added as physical damage to hand to hand from 4x to 2x
- nerfed duration of khajiit bleed passive from 5 to 3s and how much % max health damage it will do per stack from 1% to 0.75%. Sneak attacks now apply a full 3 stacks of bleed. Can no longer apply to blocking targets.
- removed some starting spells from each magic school when chosen as a major skill so each will only give 2-3. there were far too many being added and it cluttered up the menu with spells you had no intention of using for magic classes
- reduced number of starting health potions from 10 to 5
- nerfed argonian regen while in rain/water from 3/s to 2/s
- applied secondary elemental damage effects (drain speed, dmg health, damage magicka) to equivalent staves and scrolls. frost will now damage fatigue instead of drain speed
- reduced sprint fatigue cost by 2/s
- reduced jump fatigue cost to 15 (was 22)
- reduced sneak penalty applied to the player while in combat from 50 to 35
- increased maximum jump height from 140 to 164
- increased gravity force from 80 to 120
- bow fatigue costs now scale all the way to skill 100 instead of simply halving at skill level 25. at 100 marksman it will no longer cost fatigue to hold a drawn bow.

**Bugfixes**
- fixed a few missing snowy rock meshes
- fixed several conflicts with the Blackwood Company questline
- fixed Saudildorume in the Cheydinhal Newlands Lodge constantly force greeting the player after accepting his quest
- SNIFF-ed and Ordenador-ed textures and meshes from KOTN Revelations
- fixed class and specialization perks not being replaced if you changed your class with the passport
- fixed Leyawiin Lazy Cat Tavern missing mesh
- fixed issue which could cause extreme fps drops in Vilverin

## **2.0.1**

**Added**
- Oblivion Upscaled Textures BSA
- Witcher 2 Steel Armor Replacer

**Updated**
- Lore Dialogue 300 Voices

**Removed**
- Really Textured Normal Maps
- Qarls Texture Pack III Redimized - QTP3 R

**Changes**
- doomstones that correspond with a birthsign now offer a powerful and unique greater power themed for that birthsign. Sort of like an ultimate ability that you unlock through exploring the world. The powers use the same effects as this mod https://www.nexusmods.com/oblivionremastered/mods/2183?tab=description
- reworked existing birthsign powers into lesser powers, with a kiss/curse design philosophy. Also rebalanced some passives accordingly to fit better into the complete package.
- replaced many messageboxes with more convenient messages, similar to https://www.nexusmods.com/oblivionremastered/mods/141?tab=description but integrated for the modlist
- increased the frequency and pace that MOO regional factions will spawn and start invasions
- removed book writing kits and other handheld MOO crafting items as they are obsolete with OCRAFT
- added ownership and locked the bank vault door in Leyawiin
- run key is now left-alt instead of G, so galloping with horses is more convenient
- disabled Restore Magicka effect from being used in spellmaking
- integrated materials from OCRAFT - Cobl Glue into MOO's leveled lists
- integrated OCRAFT ingots into Productive Mines leveled lists
- reworked and added several new cooking recipes
- added recipes for lamp oil and to convert lanterns into lamp oil
- can use space to quickly exit most menus/messageboxes
- few sneak settings changed - max detection range reduced, can detect sound slightly more easily if player is los, skill mult increased (sneak skill matters more in relation to light and sound both on the detector and detected)
- reduced minimum level for bandit bosses from 13 to 10

**Bugfixes**
- fixed skeleton key not working with new security system
- made purchaseable cows require empty buckets to milk and provide milk from OCRAFT for crafting
- fixed some sheep from unique landscapes being unable to be sheared for wool
- fixed invisible Akatosh cuirass and gloves (lingering bug from previous Better Cities mesh update)
- reworked lighting in the Order of the Hour HQ in the Temple District to be less blinding
- moved Mysticism study book in Leyawiin Mages Guildhall to non-clipping location
- fixed missing pickaxe mesh

Details on Birthsign Changes

Birthsigns which damage an attribute will damage the attribute permanently until it is restored through potion, spell, ingredient, or visiting a chapel shrine. This is done to create a soft cooldown without a hard once per day limit, and to create more opportunities for roleplay.

- Apprentice - Those under the sign of the Apprentice regenerate magicka quickly, but their spells sometimes sputter out of control (5%). They can use the Apprentice's Folly lesser power to enhance their spellpower (30%), at further risk of mishaps (15%) for 30 seconds.
- Atronach - Those under the sign of the Atronach have great wells of magicka (+150), but do not regenerate magicka on thier own. Instead, they siphon magicka with their melee attacks. They also gain the lesser power Atronach’s Thirst, which grants 50% spell absorption but damages their own magicka reserves over 30 seconds (3/s).
- Lady - Those under the Sign of the Lady have improved willpower and restore fatigue (40 points) when they perform a well-timed block (within 0.5s). At will they may use the Lady’s Riposte, reflecting incoming weapons and spells (40% for 30s), but damaging their personality (2 points).
- Lord - Those under the sign of the Lord regenerate health (3%/2s) over time, but are vulnerable to fire (50%). They also gain the lesser power Lord’s Vigor, restoring health (6/s for 15 seconds) but gaining weakness to magic and normal weapons (100%) for the duration.
- Lover - Those under the sign of the Lover have improved personality (+15), and attackers have a chance to be calmed by their beauty. They may also use the Lover’s Kiss, a lesser power which fortifies endurance on self (25 points) and charms (15 points) for 30 seconds, but damages their fatigue (50 points).
- Mage - Those under the sign of the Mage have more magicka (+50) and mightier spells (10%). They can cast Mage's Brilliance to store their next spell to automatically cast on themselves when they enter combat and fortifying magicka (250 points), but at the cost of their willpower (2 points).
- Ritual - Those born under the Ritual are resilient to many ailments and masters of healing (+40% healing power). The Ritual's Prayer allows them to ward off evil curses and creatures, at the cost of their health (5/5s).
- Serpent - Those under the sign of the Serpent are more resistant to poison (50%) and inflict poison damage to foes who do not detect them. At will they may use the Serpent's Bite, paralyzing their target (3s) and absorbing all attributes (15 for 15s), but sacrificing endurance (2 points).
- Shadow - Those under the sign of the Shadow automatically channel their magicka (1/s) into a chameleon effect (35%) when sneaking. At will they may activate the Shadow’s Shroud, gaining invisibility (60s), but at the cost of damaged speed (2 points).
- Steed - Those under the sign of the Steed have more speed (+15) and have faster mounts. At will they can gain an incredible burst of speed and knock enemies down by running into them, but damaging their agility (2 points).
- Thief - Those under the Thief have a chance (10% of Luck) to critically hit with attacks and damaging spells, and the lesser power Thief’s Larceny, greatly enhancing their acrobatics and security and granting them a chance to avoid attacks, but at the cost of damaged luck (2 points).
- Tower - Those under the sign of the Tower reflect a portion of damage taken (15%). At will they may gain Tower's Vigilance, forcing enemies to attack them while gaining resistance to normal weapons (50%), night-eye, and detect life (15s), but becoming unable to move (5s).
- Warrior - Those under the Warrior have more strength (+10), become resistant to harm (50%) during power attacks and do more damage (+10) with them. At will they can enter the Warrior's Rage, restoring Fatigue (4/s) and fortifying Attack Damage (+10) for 30 seconds, but become exhausted after it ends.

## 2.0

**Added**
- Remastered Attributes
- Loot Menu
- Take or Equip
- Disable Detect Life During Dialog
- Magic Visuals Overhaul - Destruction particle fix
- Magic Visuals Overhaul - Fire Laser fix
- Progress Tracker - Even More Inis
- Arena Ascended - Retexture
- Ayleid Statues - Retextured
- Cultists Replace Conjurers
- Better Bound Items
- Elsweyr City Extension Voices
- Better Cities Resources - OCRAFT Integration
- Infinitum Compendium
- Star's Extended Dialogue - Roland Jenseric Voice Fix
- DLC Integration - Legacy Edition
- Horse HUD Bars - Standalone
- Companion Vilja - Non-Companion Voices
- The Blackwood Company
- Artifacts Reshoveled
- Archery Focus
- Knights of the Nine Revelation - Unvoiced Voices
- TES4Edit
- Reaction + voices addon
- Lore Dialogue 300 + voices addon
- Productive Mines
- Productive Mines - Vendors and Productive Mines - Vendors - OCRAFT
- Guild Advancement - Streamlined
- Oblivion Construction Set Extended
- Statues HD
- AV Uncapper
 - AV Uncapper Settings
- Modern Security Overhaul

**Updated**
- Maskar's Oblivion Overhaul
- Better Cities
- Kvatch Rebuilt
- OCRAFT Stations for Sale
- Crash Logger Improved
- OBSE
- Let People Speak
- AveSithis Engine Fixes

**Removed**
- Attribute Progression Redesign
- Dark Brotherhood Continued
- Curse of Hircine Resurrected
- Ivellon
- Goblin Minigames
- Guild Advancement
- Skill Diary Undone
- Wabbajack affects NPCs and Sheepstick mode
- Daedric Shrines Prodded with a Stick
- Collector Quests Revised
- Diverse Effect Icons
- Spell Renamer Basic
- The Drunken Dragon
- Unique Voices
- Explosives

**Bugfixes**
- ran Flora display fix through SNIFF which fixed several meshes that could cause crashes
- fixed prowler wolves sometimes having two pelts
- various clipping clutter disabled

**Changes**
- Sprinting is now 10% faster and consumes 2 less stamina per second
- Bound armors now carry an enchantment to fortify light and heavy armor by 15 points
- Skingrad Iron Mine will now drop the correct Iron Ingots used to craft with OCRAFT
- replaced some cape models from OOO and MOO with those from Traveling Equipment
- night brightness increased
- removed xp from crafting with Oblivion XP
- crates, sacks, and barrels in the starting ship will no longer have the stolen flag
- Oblivion XP is now disabled by default
