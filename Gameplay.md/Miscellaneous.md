## MISC CHANGES
For new mechanics which don't fit cleanly into another section.

### Travel
Fast traveling costs gold, to simulate the amount you would spend resting at inns and cost of resources. It is generally more expensive than using the alternative methods mentioned below as it is far more convenient. Fast traveling while on a horse will cut the time and cost in half.

As an alternative to fast travel, there are npcs in the basement of each Mages Guild who will teleport you to the guild of each major city. There are also npcs at each stable who will take you to other stables by carriage, and npcs at each dock location who will transport you by boat. 

### Lock Bashing
Locks can be bashed by attacking them with your weapon or fists. Your weapon or gloves/you will be damaged. Blunt and heavy weapons are best suited to the task. Player strength, weapon skill, and current fatigue are all accounted for in the formula. Power attacks give a 3x  bonus, but deal more damage back to the weapon/gloves/you. Bashing locks is a crime and can't be attempted while sneaking.

### Needs
The list has simple and balanced bonuses for eating, drinking, and sleeping regularly. Encourages roleplaying, without burdening you with negative effects if you don't. 

Eating or drinking any item considered to be food by the game contributes to your 'food pool', based on the weight and value of the item. Once your food pool reaches a threshold, you will be considered Well Fed. Whist 'Well Fed', you will gain slow Health regeneration outside of combat, which makes eating a meal before setting off on a dungeon crawl very beneficial. Your food pool depletes over time and when it reaches zero, you will no longer be Well Fed. Cooked foods crafted from the Cooking Pot also offer long lasting attribute buffs, in addition to filling your hunger meter.

Sleeping in a bed provides a 'Well Rested' bonus that increases Fatigue by 50 points for a long period of time. Sleeping in a safe indoors location provides the bonus for 12 hours, and any other location provides it for 6 hours. You will also gain rested experience based on the amount of time slept.

### Horsemanship
A brand new skill is added which gradually increases horse acceleration, handling and jump height. It is increased by simply riding horses, as well as some other interactions and has a full set of perks:

    Apprentice: Making small turns will no longer decrease galloping speed
    Journeyman: Unlocks rearing.
    Expert: Unlocks strafing.
    Master: Horse can run on water, but only when galloping.

Trainers, skill books, and enchanted items with Fortify Horsemanship can be found.
  - Walking - default horse walking speed had been slightly increased, but otherwise unchanged.
  - Trotting - a new motion, this is basically “fast walking” - a middle ground between walking and galloping.
- Galloping - this is the default “running” motion, heavily tweaked. Overall faster then in vanilla, and horse speed will gradually increase over time up to a certain maximum. Acceleration is based on Horsemanship skill. Top speed is based on horse breed.
   - Turning - small turns will decrease max galloping speed, unless Horsemanship skill level is 25+. Holding turn controls for longer will decrease speed to trotting.
   - Inertia - horses no longer instantly stop after galloping, instead a special stopping animation is performed.
   - Rearing - a new motion, unlocked at Horsemanship skill level 50 and activated by jump key when standing. Rearing can be used to gain a starting speed boost and go straight to galloping.
   - Strafing - a new motion, unlocked at Horsemanship skill level 75 - hold Block and use left/right controls to strafe.

Saddlebags

    Each owned horse gives access to saddlebags. They can be accessed by pressing the inventory key, while having owned horse under the crosshair.
    Saddlebags capacity is limited to 500 units (configurable). Capacity is shown in container UI.
    Contents are shared between all owned horses.
    When a horse dies, all saddlebags contents are moved to it’s corpse. They can NOT be retrieved by accessing another horse’s bags at this point.
    An extra UI element shows saddlebags capacity while in inventory menu. Compatible with DarNified UI only.



Whistle

    Press a custom key (Default: H) to whistle to your horse and have it come to you and follow. Press again for it to stop following.
    If the horse is too far away, it will be teleported somewhere out of view (configurable).
    By default, this only works in Tamriel worldspace. An option is available to have horse teleport into any exterior worldspace. Regardless of the setting, horses will never come to interiors or in Oblivion worlds.

### Gods and Worship
You will often find shrines to different divines in homes and public spaces depending on the region. The Colovians, a militaristic and rustic people, comprise of the bulk of the Legion. The martial Colovians may have shrines to the Nine Divines, but these are scarcer than in the Heartlands. Cities dominated by Colovian subculture include Chorrol, Anvil, and Skingrad (Kvatch has been left untouched).     

The cosmopolitan Nibenese, by contrast, are esoteric, philosophizing, and religious.  The Nibenese will have often a multitude of shrines in their homes and businesses.  Many Nibenese will have shrines related to more obscure cults, such as shrines to Cuhlecain (the Cult of Emperor Zero), Reman Cyrodiil (founder of the 2nd Empire), Alessia and Morihaus (leaders of the rebellion against the Ayleids), and shrines to various hero and animal cults.   Cities dominated by Nibenese subculture include Leyawiin, Bravil, Cheydinhal, Bruma, and the Imperial City.

Other lore-appropriate shrines have been added:

- Nords will often have a shrine to Tiber Septim or Kynareth.

- Mages Guild halls and the Arcane University will have shrines to Julianos.

- Orcs may have a shrine to Malacath.

- Many merchants and businesspeople throughout Cyrodiil will have a shrine to Zenithar.

- Weynon Priory and Cloud Ruler Temple will have a shrine to Tiber Septim.

- The Temple of the Ancestor Moths will have a shrine to Julianos.

- A few Dunmer will have shrines to the Reclamation Daedra: Azura, Mephala, and Boethiah. 

- Members of the Thieves Guild may have a shrine to Nocturnal, hinting at their true allegiance.

- Sleeper agents of the Mythic Dawn may have a shrine to Mehrunes Dagon in their dwellings, hinting at their true allegiance.

- Members of the Dark Brotherhood may have a shrine to the Night Mother in the guise of the Lucky Old Lady, hinting at their true allegiance.

Each Divine Altar restores one attribute up to 100 points, cures disease, and restores health. The attribute restored is the same as their blessing. Altars of the Nine will restore all attributes. Blessings of the Divine have also been reworked, their bonuses are as follows:
| Divine    | Blessing | 
|:--------------:|:-------------:|
| Akatosh | Fortify Speed 5 points for 6480 seconds.
| Arkay | Fortify Health 15 points for 6480 seconds.
| Dibella | Fortify Personality 5 points for 6480 seconds.
| Julianos | Fortify Intelligence 5 points for 6480 seconds.
| Kynareth | Fortify Agility 5 points for 6480 seconds.
| Mara | Fortify Willpower 5 points for 6480 seconds.
| Stendarr | Fortify Endurance 5 points for 6480 seconds.
| Talos | Fortify Strength 5 points for 6480 seconds.
| Zenithar | Fortify Luck 5 points for 6480 seconds.

Wayshrine Blessings are twice as potent. Additionally, once per day you can enhance a bandage at an Altar of the Nine, improving the effects. 

Each Nine Divines faction and 2 Knightly Orders can be joined. Joining a faction requires you to have basic knowledge about one of the faction's required skills, and you must perform a pilgrimage to the god's wayshrine. Ask the priests to know where you may find a wayshrine.

You can join only ONE god faction OR one Knightly Order. You cannot join both a Knightly Order and its associated priesthood. The benefits of joining a faction are that you have reduced prices for the healing service, lodgings in the temple/HQ, access to privileged services (For some religions) and the god/Knightly Order's outfit. The friends of the god you worship are your friends. His enemies are your enemies. Ghosts in your faction's Undercroft will not attack you. Killing a member of your faction or stealing will result in being expelled. Once expelled, you cannot join again and you cannot switch to another god. There are no quests or possibility of advancements, it's just meant for roleplaying.

### Magical Stones

Doom Stones each have a unique greater power thematic with the birthsign they correspond to and a kiss/curse design, as a sort of ultimate ability you unlock through exploration. You may only have one doomstone power at a time. The effects of each stone are as follows.

- Lady- Womb of Rebirth - Through the Lady you are given a chance at rebirth, fully restoring all your attributes. However, the process of rebirth leaves you weakened for a time, draining all of your attributes by 25 for 15s.
- Lord - Rallying Cry - Rally yourself, fortifying endurance by 150 and becoming immune to fear for 120 seconds. However, you become 100% weaker to disease and poison for the duration, the bane of all kings.
- Steed - Icarian Flight - Call upon the Steed to gallop across the sky, fortifying your speed by 1,000 and your acrobatics by 25,000 for 30s. Hopefully you land before the blessing wanes.
- Warrior - Berserker Rage - Become a whirlwind of flesh and steel, fortifying your strength, blade, blunt, and hand to hand by 50 for 120 seconds. Each time you succumb to your rage you lose some of your humanity and become no better than the mindless beasts, damaging your intelligence by 10 points.
- Apprentice - Arcane Fracture - Unleash a nova of pure arcane energy, causing enemies to be 100% weaker to magic in a 100 yard radius for 60 seconds. However, due to your reckless spellcasting you also become 100% weaker to magic for the duration.
- Atronach - Null Field - Create a zone of no magicka, silencing, dispelling, and fully depleting magicka of all targets (including yourself) in a 100 yard radius for 60 seconds.
- Mage - Elemental Triune - Conjure a massive storm of elemental power, dealing 10 points of fire, frost, and shock damage in a 75 yard radius for 60 seconds. The storm batters your own defenses, causing you to be 50% weaker to the elements for the duration.
- Ritual - Profane Ritual - Drain 25 points of your own health for 120s while conjuring a full suit of bound armor, a mace, and a shield, and reanimate on touch for the duration of the drain effect.
- Lover- Infatuation - Command any humanoid and restore their health, magicka, and fatigue by 3 for 120s. However when the command ends they will be frenzied for another 30s, attacking anything in sight including you.
- Shadow- Aspect of Terror - Demoralize targets in a 100 yard radius causing them to run in fear for 60s. In doing so you lose your ability to sneak, creating a 600 yard area of light centered on yourself for the duration.
- Thief - Dance with Fate - Make a deal with fate, becoming 100% resistant to magic and normal weapons for 30s, but draining your luck by 50 points for the duration.
- Tower -  Fortified Walls - Envelop yourself with spiked and impenetrable walls, reflecting 85% of incoming damage for 30s, but paralyze yourself for 15s.
- Serpent - Star Curse - Curse a target with 500% weakness to poison for 60s and paralyze them for 15s, but halt your natural regeneration, damaging your health, magicka, and fatigue by 1/s for 60s.


Heaven Stones give a unique passive effect that stacks with the effects from other Heaven Stones, however have a fame requirement to activate. The effects of each stone are as follows.

- Aetherius - Resist Magic 5 points
- Dragon - Fortify Health, Magicka, Fatigue 10 points
- Jode - Fortify Health 20 points
- Jone - Fortify Sneak & Acrobatics 10 points
- Magnus - Fortify every magic skill 5 points
- Shezarr - Fortify Block, Heavy & Light Armor, and Armorer 5 points
- Sithian - Fortify Speech & Mercantile 15 points

Rune Stones no longer give a piece of bound armor and a bound weapon, but instead each gives a powerful, unique and permanent effect related to one of the three major specializations (combat, magic, stealth).

- Reman - Your power attacks that strike somebody who's blocking damages their shield's health by an amount equal to 3 times your skill in the weapon you're using. If they're blocking with a weapon, rather than a shield, the damage to the equipment is quartered.
- Hestra - The boon grants you a passive 35% elemental shield to either Fire, Frost, or Shock. The elemental shield changes whenever you cast a spell featuring Fire, Frost, or Shock damage, to reflect the element used (cast a fire damage spell and it changes to fire shield, for example). If the spell features multiple damage types then it chooses what element based on priority (earliest in the list governs the resistance): Fire > Frost > Shock.
- Sidri-Ashak - After spending an uninterrupted span of 10 seconds in darkness, you gain 25 points of Chameleon. This effect lasts until you've spent 6 uninterrupted seconds outside of darkness.

### Drugs & Alcohol
Alcohol offers a variety of benefits. Wine tends to buff magicka and personality while hard liquor and beers tend to buff fatigue and physical traits.

Your character can now become addicted to Skooma. Most effects have been removed from the actual potion and added via script. The only effects you will see on the potion bottle are positive. In theory, it seems perfectly harmless on the outside, until you find out about the addiction and other effects. As you become addicted, there should be an "Addicts Diary" added to your Inventory. This will give you key insights into what level you are at, and how long you have until you absolutely must consume before going into withdrawal. You will gain an increasing fortify speed effect while at the same time increasingly draining your willpower. Each addiction level has a requirement for skooma to be consumed, thus addiction can get quite expensive and without feeding that addiction the player goes into withdrawal. However it can be refined using a recipe at the Cooking pot. If you become addicted and do not continue to drink Skooma, you will begin to suffer withdrawals. There are 5 levels of withdrawal symptoms, with each progressively draining more of your attributes. The higher level your addiction is, the higher level of withdrawals you will suffer. The only real cure of Skooma Addiction is to go through the levels of withdrawal and cure yourself. It's a choice that has to be made...although judicious use of WAIT and SLEEP can reduce the impact if you really want to disrupt the immersion.

### Gambling
There are NPCs in all the main cities that will play chance games with the player. Look for them around plazas, around city landmarks or at taverns and inns. They have individual AI schedules, different levels of difficulty and available gold. Once they run out off gold they will go to work at certain times unless the player donates them money or until they gain their own gold back. There is one NPC that has unlimited gold, but is very hard to beat. You can also ask "In the mood for a game?" to any NPC at a tavern or inn, provided they like you enough and that they have at least ten septims. The gold on these NPCs is handled by the game itself via leveled lists. There are 5 potential games they can play, which is completely random. 

- Guess How Many Septims:
Pretty much what the title suggests. There are two variations of the game. One where the NPCs hide up to five Septims in their hand and another version where you hide up to five Septims in your hand. The first version depends on your real life luck, meaning there is only one right choice. The second version depends on the NPCs luck. The payout is the choice selected, not the actual septims in hand. Meaning if you thought he had 3 septims, you will pay 3 septims and vice versa.

- Double or Nothing:
Basically a coin flip. Both parties bet 10 septims. Either you or the NPC will get to flip the coin. Whoever doesn't flip the coin calls heads or tails. If you get a match you get 20 septims. Depends on the caller's luck.

- Dice: Blates:
The game is played with a pair of six-sided dice and centers on various forms of the sum quantity 8. The score is the sum of the two face up values of the dice. The player with the lowest score wins. The various forms of the sum 8 have special meaning. 4 and 4 is "Blates", and is worth 0. Certain victory, unless the opponent also rolls Blates. 3 and 5 form a "Gentleman's Eight" which is worth 1, making it the best roll in the game besides Blates. 2 and 6 form a "Pauper's Eight" which is worth 13, making it the worst roll in the game. It is impossible to actually roll 8 in Blates. If any players roll the same value in a round, they should take turns rolling against each other until the tie is broken. This is commonly referred to as a "roll off".

- Dice: Parity:
A 10 Septim bet is made on either an odd or even roll. Player rolls 1 die.

- Dice: Double Parity:
Same as Parity, but two dice are rolled. If a double is rolled the bet is doubled to 20.

- High Stakes:
Any NPC with a luck higher than 60 will give the option to play games at higher stakes. As far as I know all default NPCs in Oblivion have a luck of 50. So this should only affect the new gamblers with luck higher than 60 (or any other mod added NPC who has high luck and happens to be hanging in a tavern or inn. The options are 2x, 3x, 4x and one special gambler has 10x option. These option only show up if both parties can afford the larger transactions.
