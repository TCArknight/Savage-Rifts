Sources: 
Coalition Field Manual (Complete)
Fan Material from G+ Community

Known Issues:

History:
06/15/19
New:
- New setting on Configure Hero to preclude races from the Sci-Fi Companion
- Use generic Racial Tab instead of Rifts Racial Tab. 
- Partial implementation of output on the BBCode Statblock output for Output in format for use in forum games on SavageRifts.com
- Replacement for Skills tab to allow for selection of languages on the tab
- Rework of Flame Wind Dragon Hatchling
  * Limited Metamorphosis tags Rifts.DragonForm and Rifts.HumanForm which allow for conditional bootstraps of Dragon-Specific Abilities
- Rework of Breed Advantage Edge
  * Each breed is a Simple component with
    - Helper.Bootstrap tag 
    - BreedAdv.<name of the breed> tag

Added: 
- Adjustment for Skill Points Spent
- New ArmorSpecial component and ArmorRifts compset
  - adds following fields to Rifts-Specific Armor
    - arToughness: value to modify wearer's toughness by when equipped
    - arSpecial: Special details about Armor
    - arSpecDisp: used to display synthesis of Cover tags and new ArmorSpecial.? tags
    - arCover: holds text synthesis of display for ArmorLoc.?
- Rifts Statblock includes display of special features for armor
- Extended Character sheet
  - Armor displays increased to include display of coverage and special properties
- Body Armor selections for Hero's Journey provide modification of selected armor. 
- Close Combat Weapon selections for Hero's Journey provide modification of selected Melee Weapon (not natural weapons). 
- Ranged Combat Weapon selections for Hero's Journey provide modification of selected Ranged Weapon (not natural weapons) 

Fixed:
- Creatures created with core Rifts settings treated as Human in addition when saved to portfolio and reloaded (Human tags, abilities, etc.)
- Running Die missing for various edge/racial abilities 
- Cyber-Knight available powers incorrect
- Combat Cyborg unable to select edge or attribute for Shadow of Themselves
- Training: Combat Edge entry for Hero's Journey provides too many choices
- Exceptional Rapid Recharge shows as "Impr Rapid Recharge"
- Dragon Hatchling is nable to use advance to purchase/upgrade abilities


History:
05/05/19
New:
- New setting on Configure Hero to preclude races from the Sci-Fi Companion
- Use generic Racial Tab instead of Rifts Racial Tab. 
- Replacement for Skills tab to allow for selection of languages on the tab
- Rework of Flame Wind Dragon Hatchling
  * Limited Metamorphosis tags Rifts.DragonForm and Rifts.HumanForm which allow for conditional bootstraps of Dragon-Specific Abilities
- Rework of Breed Advantage Edge
  * Each breed is a Simple component with
    - Helper.Bootstrap tag 
    - BreedAdv.<name of the breed> tag

Added: 
- Adjustment for Skill Points Spent
- New ArmorSpecial component and ArmorRifts compset
  - adds following fields to Rifts-Specific Armor
    - arToughness: value to modify wearer's toughness by when equipped
    - arSpecial: Special details about Armor
    - arSpecDisp: used to display synthesis of Cover tags and new ArmorSpecial.? tags
    - arCover: holds text synthesis of display for ArmorLoc.?
- Rifts Statblock includes display of special features for armor
- Extended Character sheet
  - Armor displays increased to include display of coverage and special properties
- Body Armor selections for Hero's Journey provide modification of selected armor. 
- Close Combat Weapon selections for Hero's Journey provide modification of selected Melee Weapon (not natural weapons). 
- Ranged Combat Weapon selections for Hero's Journey provide modification of selected Ranged Weapon (not natural weapons) 

Fixed:
- Running Die missing for various edge/racial abilities 
- Cyber-Knight available powers incorrect
- Combat Cyborg unable to select edge or attribute for Shadow of Themselves
- Training: Combat Edge entry for Hero's Journey provides too many choices


History:
12/08/18
New:
Added new tag Helper.Domain skill to specific Knowledge skills
Added Helper.Domain skill tag to zSkills, zSkillsDom portals as well as the position script for zSkillPick template for proper display on Extended character sheet in the zSkillsDom portal
Added Arcane2 as the Secondary Arcane Background component
Added Secondary Arcane tab (savrifts_tab_arcane2.dat) for display of powers associated with the new secondary background
Added secondary pool of Power points and tracker for secondary ABs

Fixed:
Arcane powers bootstrap Mega-Power versions for display when Rifts.MegaPowerValid tag present on Hero
Framework: Mystic - proper handling of primary and secondary ABs, Framework Abilities and Complications
Framework: Techno-Wizard - fixed Framework abilities, complications
Power Point Tracker now displays PPE/ISP as appropriate
Cyberknight now doesn't begin with having spent skill points for Fighting and Arcane (Psionics) skills
HJ - Education: Politics gives +2 to Persuasion

10/04/18
Fixed:
Tag/Thing Id strings lengths updated for new Herolab Version 8.7

9/20/18
Fixed:
Statblock - Hero's Journey header showing when no selections made
M.A.R.S. Operator - Ace, McGyver Edges showing prereqs not met
M.A.R.S. Psi-Operator - Unable to select Mind Melter Powers

8/5/18
New:
Fan Material from G+ Community

Fixed:
Burster - Free Psionics skill costing Skill Points
Master of Magic Edge doesn't appear to be seeing Knowledge Arcana
Mind Melter not properly getting the Arcane Background (Psionics) edge.
Combat Cyborgs/Power Armor - Encumbrance/Load Limit not using Super Strength 
Flame Wind Dragon Hatchling - Doesn't require Dragon Hatchling Race

2/12/18
New:
Framework: Ley-Line Walker
Framework: Mind Melter
Framework: Shifter
Framework: Techno-Wizard

2/11/18
New: 
Seperate PPE, ISP Tracker
Add second choose table to Framework tab to allow for two different types or selections
Bootstrap second Expression helper
Rename initial Expression helper

Fixed: 
M.A.R.S - Rogue Scholar not allowing selection of Knowledge Skills
NG-S2 Survival Pack updated to allow storage in other containers.
