# Jendavudd Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(SKYSHRINE_ARMOR.Plate_Helmet, 31182), 

quest_helper:melee_chest(SKYSHRINE_ARMOR.Breastplate, 31183), 

quest_helper:melee_arms(SKYSHRINE_ARMOR.Plate_Vambraces, 31184), 

quest_helper:melee_bracer(SKYSHRINE_ARMOR.Plate_Bracer, 31185), 

quest_helper:melee_gloves(SKYSHRINE_ARMOR.Plate_Gauntlets, 31186), 

quest_helper:melee_legs(SKYSHRINE_ARMOR.Plate_Greaves, 31187), 

quest_helper:melee_boots(SKYSHRINE_ARMOR.Plate_Boots, 31188), 
}

## Dialog

if( **Faction is** >= Ally ) then 


**You say:** `hail`




>**Jendavudd Fe-Dhar says:** Greetings to you. I seek the service of a powerful warrior. If you are not what I seek leave me be.


**You say:** `warrior`




>**Jendavudd Fe-Dhar says:** Excellent. I admire strength and ferocity. Life is but a series of battles, is it not?


**You say:** `battle`




>**Jendavudd Fe-Dhar says:** We share the same view then. I wish to test your skills in battle. Not with me of course, for I will destroy you where you stand. Instead I wish for you to retrieve some trinkets for me and once I have them I will reward you handsomely with a helm, a breastplate, armplates, bracers, gauntlets, greaves, or boots.


**You say:** `helm`




>**Jendavudd Fe-Dhar says:** All I require are an unadorned plate helmet and three pieces of crushed coral. This should be a small task for one such as you. Go now and I shall await your return.


**You say:** `breastplate`




>**Jendavudd Fe-Dhar says:** As the resolve of your discipline and strength shall endure through a battle, so shall this breastplate. All I required are an unadorned breastplate, and three flawless diamonds. Do this quickly so that you may return to the field of battle.


**You say:** `armplate`




>**Jendavudd Fe-Dhar says:** So, a pair of armplates is what you require? Well, I require unadorned plate vambraces, as well as three flawed emeralds before you may receive them. May your deeds be spread throughout the lands!


**You say:** `bracer`




>**Jendavudd Fe-Dhar says:** Bracers for the mighty? Retrieve these components and I shall forge the item for you. Bring me an unadorned plate and three crushed flame emeralds.


**You say:** `gauntlet`




>**Jendavudd Fe-Dhar says:** Mighty gauntlets to aid in obliterating your foes, eh? It is no easy task but I shall require a pair of unadorned plate gauntlets and three crushed topaz.


**You say:** `greave`




>**Jendavudd Fe-Dhar says:** Strength and balance are important, are they not? I shall help give you an advantage with these leggings. Gather for me three flawed sea sapphires and a set of unadorned plate greaves.


**You say:** `boot`




>**Jendavudd Fe-Dhar says:** A pair of boots you shall have once you have gotten a pair of unadorned plate boots as well as three pieces of crushed black marble.



else 


>**Jendavudd Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.
 
## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success) 