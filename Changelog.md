## **2.0.6**

**Added**
- Magic Magnitude Multipliers
- Customizable Magic Progression
- Night Sky Fire and Ice
- Oblivion Stutter Remover - replaced the heap mode from ORC

**Removed**
- Decorator Assistant - redundant and can cause crashes with Enhanced Grabbing
- Let People Speak - causes crashes
- Channeling Staves - redundant
- Glowing Plants & Mushrooms
- Best Combined Night Sky

**Changes**
- Intelligence will now also scale spellcasting magnitude by a percentage. You can view the amount in the misc stats screen.
- Willpower will now also scale magic resistance (or weakness if below 25) by a percentage. You can view the amount in the misc stats screen.
- Spell magnitude is now increased by 10% when wielding any staff, and decreased by 10% when wielding a weapon or shield. There is no penalty or bonus when empty handed.
- Hoarfrost Castle quest now will only start in Chorrol or Bruma, or if the player visits the castle
- Highwood quest now will only start in Anvil or if the player visits the farm
- nerfed essential death time from 60 to 15 seconds so you don't have to wait around if an essential quest npc goes down
- readded old snow texture, edited snowy rock textures to blend better
- renamed "tunic of the dead" and "hood of the dead" to "necromancer robe" and "necromancer hood"

**Bugfixes**
- silver veins no longer can drop platinum and gold veins can no longer drop copper
- fixed bug preventing you from closing the inventory menu
- removed follow dialogue from random nameless mages guild npcs

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
