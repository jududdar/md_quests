# Kragek Thunderforge


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(KAEL_ARMOR.Plate_Helmet, 25433), 

quest_helper:melee_chest(KAEL_ARMOR.Breastplate, 25434), 

quest_helper:melee_arms(KAEL_ARMOR.Plate_Vambraces, 25435), 

quest_helper:melee_bracer(KAEL_ARMOR.Plate_Bracer, 25436), 

quest_helper:melee_gloves(KAEL_ARMOR.Plate_Gauntlets, 25437), 

quest_helper:melee_legs(KAEL_ARMOR.Plate_Greaves, 25438), 

quest_helper:melee_boots(KAEL_ARMOR.Plate_Boots, 25439), 
}



## Dialog

if ( **Faction is** >= Ally) then


**You say:** `hail`




>**Kragek Thunderforge says:** Greetings to you. I seek the service of a powerful warrior. Are you a warrior? If not then be gone.


**You say:** `warrior`




>**Kragek Thunderforge says:** Excellent. I see that you are a seasoned veteran of many battles. I admire your strength and ferocity. Life is but a series of battles, is it not?


**You say:** `series of battle`




>**Kragek Thunderforge says:** We share the same view then. I wish to test your skills in battle. Not with me of course, for I will destroy you where you stand. Instead I wish for you to retrieve some trinkets for me and once I have them I will reward you handsomely with a helm, a breastplate, armplates, bracers, gauntlets, greaves, or boots.


**You say:** `helm`




>**Kragek Thunderforge says:** All I require are an ancient tarnished plate helmet and three crushed coral pieces. This should be a small task for one such as you. Go now and I shall await your return.


**You say:** `breastplate`




>**Kragek Thunderforge says:** As the resolve of your discipline and strength shall endure through a battle, so shall this breastplate. All that is required are an ancient tarnished breastplate, and three flawless diamonds. Do this quickly so that you may return to the field of battle.


**You say:** `armplate`




>**Kragek Thunderforge says:** So, a pair of armplates, is what you require? Well, I require an ancient tarnished plate vambraces as well as three flawed emeralds before you will receive your prize.


**You say:** `bracer`




>**Kragek Thunderforge says:** Bracers for the mighty? Retrieve these components and I shall forge the item for you. Bring me an ancient tarnished plate bracelet as well as three crushed flame emeralds.


**You say:** `gauntlet`




>**Kragek Thunderforge says:** Mighty gauntlets to smite your foes for the glory of the greater good. It is no easy task but I shall require a pair of an ancient tarnished plate gauntlets and three crushed topaz.


**You say:** `greave`




>**Kragek Thunderforge says:** Sturdy are the pillars that support the temple. I shall make you as strong with these leggings. Gather three flawed sapphires of the sea and a set of ancient tarnished plate greaves.


**You say:** `boot`




>**Kragek Thunderforge says:** A pair of boots you shall have once you have gotten a pair of an ancient tarnished plate boots and a set of three crushed pieces of black marble.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Kragek Thunderforge says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Kragek Thunderforge says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.




## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success) 