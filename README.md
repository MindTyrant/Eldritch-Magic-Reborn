# Eldritch Magic Reborn
### Rebuilt Version of Eldritch Magic, Originally by AbdelAdrian
## By MindTyrant

v0.1.2.8

A mod for BG2EE and EET.  Some features may work with IWDEE. Currently, only windows platform is supported. Any volunteers who wish to help expand compatibility to other games and platforms should contact me at mindtyrant1024@gmail.com.

Mod Features
 
* Congenio's Pebble Collection - Allows multiple Ioun stones to stack without (*permanently*) using any equipment slots. Simply equip the stone to the headslot set it, and then use its item ability to put it in orbit. At this point it will disappear from both your headslot and inventory. You can remove its benefits and restore the stone to your inventory with its provided innate ability.  

  WARNING: Ioun stones that use Opcode "Stat: Maximum HP Modifier [18]" work differently than others. For the HP modifier to be removed when the Ioun stone is, the HP modifier cannot be saved and loaded. In other words, if you save with the Pale Green Ioun Stone and/or Wong Fei's Ioun Stone equipped in orbit, you must equip them again upon loading to receive the HP modifier. 

  UPDATED for partial compatiblity with Visual Ioun Stones from the [d0tweak](https://github.com/Pocket-Plane-Group/D0Tweak) mod. For some reason, Obsidion and Malla's stone display near perfect, while the others seem to play so fast that multiple copies of the same stone appear to be rendered. When the game is paused, you can see only one copy is rendered.  I tried to slow them done in the .vvc file, it did not seem to have an effect. Please contact me if you know how to resolve this error.
  
  Note that if two stones that use the same .vvc file, it will only render one of them. This affects the following groups of Ioun Stones:

  - Bronze Ioun Stone and Golden Ioun Stone
  - Trollblood Ioun Stone, Pale Green Ioun Stone, and Wong Fei's Ioun Stone
  - Blood Red Ioun Stone and Lavender Ioun Stone
  - Pearly White Ioun Stone, Silver Ioun Stone, and Purification Stone

* Eldritch Armors - Gives the different Elven Chain suits more powers based on their enchantment level.  Each suit now provides unique bonuses based on their lore, on top of providing superior protection without disabling spellcasting. 

* Bladesinger Kit - Based on the 2<sup>nd</sup> edition material found in the *Complete Book of Elves*, Bladesingers are elven fighter/mages known for the haunting sounds made by their weapons with only the slightest bodily movement. It uses an alternative to Single Weapon style, which is incorporated in the form of bladesongs. It was rebalanced for Baldur's Gate to account for the loss of the miscellaneous bonuses from an offhand weapon or shield items, and the superior weapon styles found there. Certain concessions were also made because of the limited ruleset it uses. Note the names for its various abilities were "borrowed" from similar abilities in other editions. Only the tiger clan, who are masters of the long sword, were included in this release. Other clans who master other weapons may be included with future releases if there is sufficient interest. 

  NOTE: "Song of Victory" now uses the "Able to Poison Weapons" icon and the Bladesong portrait icons have been copied and renamed. The Character Sheet will display "Song of Defense," "Song of Victory," or "Song of Celerity" instead of "Defensive Harmony," "Able to Poison Weapons," or "Haste." Contact me if you can help design unique icons for Bladesongs.

BLADESINGER KIT: Of the roving Elves, there are few as deadly as the Bladesingers of Clan Lion. They are experts in the long sword and have spent their lives studying their chosen weapon. They have also learned to cast spells while engaged in combat, and thus they double their might.

Advantages:
- +1 to hit and damage rolls. 
- May achieve High Mastery (four slots) in long swords.
- May use the three Bladesong abilities. Only one bladesong may be used each round, and its use does not count as your spell for the round. To receive the effects from a bladesong requires a one-handed melee weapon and an empty off-hand, and may not be used with a shield, ranged weapon, or armor heavier than chain mail. Using a bladesong removes the effects of any other bladesong, and for 8 hours provides the following effects:

  SONG OF DEFENSE: Grants a +2 bonus to Armor Class. This bonus improves to +3 at fighter level 11 and +4 at fighter level 21.

  SONG OF VICTORY: Grants a +2 to hit rolls. This improves to +3 at fighter level 11 and +4 at fighter level 21.

  SONG OF CELERITY: Grants a -1 bonus to Speed Factor with weapons. This bonus to Speed Factor improves to -2 at fighter level 11 and -3 at fighter level 21.

- Blindfighting: Immune to blindness.
- Countersong: Gain a +1 bonus to Saving Throws vs. Spell. This bonus improves by +1 for every six mage levels. 
- Arcane Fury: At mage level 5, inflicts critical damage on an attack roll of 19 or 20. 
- Arcane Strike: At mage level 15, may make an additional attack every other round. 

Disadvantages:
- Race restricted to Elf.
- One-handed Casting: Suffers a -2 penalty to casting speed.
- Incurs an additional -1 nonproficiency penalty to hit rolls (for a total of -3).
- Starts with two fewer starting weapon proficiencies, earns additional weapon proficiency at every four levels instead of every three.
- May not exceed Proficiency (one slot) in weapons (except for long sword).
- May not place any slots in Single-Weapon Style. 
- May not exceed Proficiency (one slot) in any other fighting style. 
- Alignment restricted to any lawful or good.
