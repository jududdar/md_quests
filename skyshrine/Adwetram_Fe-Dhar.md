# Adwetram Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS={

quest_helper:melee_helmet(SKYSHRINE_ARMOR.Plate_Helmet, 31119), 

quest_helper:melee_chest(SKYSHRINE_ARMOR.Breastplate, 31120), 

quest_helper:melee_arms(SKYSHRINE_ARMOR.Plate_Vambraces, 31121), 

quest_helper:melee_bracer(SKYSHRINE_ARMOR.Plate_Bracer, 31122), 

quest_helper:melee_gloves(SKYSHRINE_ARMOR.Plate_Gauntlets, 31123), 

quest_helper:melee_legs(SKYSHRINE_ARMOR.Plate_Greaves, 31124), 

quest_helper:melee_boots(SKYSHRINE_ARMOR.Plate_Boots, 31125) 
}

## Dialog

if ( **Faction is** > Warmly) then 


**You say:** `hail`




>**Adwetram Fe-Dhar says:** I wish to speak only to the knights called paladins. If you are what I seek do you wish to partake of my quests?


**You say:** `partake`




>**Adwetram Fe-Dhar says:** Excellent. By serving my cause, you, in turn, will further your own. I require certain components to aid me and if you bring them to me, I shall reward you for your honorable service. You may choose from among these items: a helm, a breastplate, armplates, bracers, gauntlets, greaves, and boots.


**You say:** `helm`




>**Adwetram Fe-Dhar says:** All I require are an unadorned plate helmet and three pieces of crushed coral. This should be a small task for one such as you. Go now and I shall await your return.


**You say:** `breastplate`




>**Adwetram Fe-Dhar says:** As the resolve of your faith protects you, so shall this breastplate. All that is required are three flawless diamonds and an unadorned breastplate. Do this quickly so that you may return to the field of battle.


**You say:** `armplate`




>**Adwetram Fe-Dhar says:** So, a pair of armplates is what you require? Well, I require unadorned plate vambraces and three flawed emeralds before you may receive it.


**You say:** `bracer`




>**Adwetram Fe-Dhar says:** Bracers for the mighty? Retrieve these components and I shall forge the item for you. Bring me three crushed flame emeralds and an unadorned plate bracer.


**You say:** `gauntlet`




>**Adwetram Fe-Dhar says:** Mighty gauntlets to smite your foes for the glory of the greater good! It is no easy task but I shall require a pair of unadorned plate gauntlets as well as three crushed topaz.


**You say:** `greave`




>**Adwetram Fe-Dhar says:** Sturdy are the pillars that support the temple. I shall make you just as strong with these leggings. Gather unadorned plate greaves and three flawed sea sapphires.


**You say:** `boot`




>**Adwetram Fe-Dhar says:** A pair of boots you shall have once you have brought me a pair of unadorned plate boots, and three pieces of crushed black marble.


else 


>**Adwetram Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.

## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success) 