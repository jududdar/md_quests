# Komawin Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(SKYSHRINE_ARMOR.Leather_Cap, 31189), 

quest_helper:melee_chest(SKYSHRINE_ARMOR.Leather_Tunic, 31190), 

quest_helper:melee_arms(SKYSHRINE_ARMOR.Leather_Sleeves, 31191), 

quest_helper:melee_bracer(SKYSHRINE_ARMOR.Leather_Bracelet, 31192), 

quest_helper:melee_gloves(SKYSHRINE_ARMOR.Leather_Gloves, 31193), 

quest_helper:melee_legs(SKYSHRINE_ARMOR.Leather_Leggings, 31194), 

quest_helper:melee_boots(SKYSHRINE_ARMOR.Leather_Boots, 31195), 
}



## Dialog

if ( **Faction is** > Warmly) then 


**You say:** `hail`




>**Komawin Fe-Dhar says:** Greetings to you. I seek one that has chosen the path of monkhood. What do you call yourself?


**You say:** `monk`




>**Komawin Fe-Dhar says:** Good. I had hoped you were one. As seeker of the way you are in constant training to push yourself to your physical and mental limits. It is an admirable quality and I wish to aid you. I will provide you with a cap, a tunic, sleeves, bracers, gloves, leggings and boots


**You say:** `cap`




>**Komawin Fe-Dhar says:** I shall weave one of exceptional quality for you but you must gather the items first. I require an unadorned leather cap and three pieces of crushed coral.


**You say:** `tunic`




>**Komawin Fe-Dhar says:** You shall be an imposing force with this tunic. Solid as the unmoving mountains, it shall protect you. Once I have gained a set of three flawless diamonds and an unadorned leather tunic.




**You say:** `sleeve`




>**Komawin Fe-Dhar says:** As the mighty stone that parts the flow of water, so shall these sleeves divert harm against you. Bring me a pair of unadorned leather sleeves and three flawed emeralds.


**You say:** `bracer`




>**Komawin Fe-Dhar says:** For a bracer I shall require three crushed flame emeralds and an unadorned leather bracelet. Bring me these items and the reward shall be yours to keep.


**You say:** `glove`




>**Komawin Fe-Dhar says:** Your hands are like the wind, everflowing and moving. Subtle one moment, then a howling wind raining blow upon blow to your foes. These gloves shall aid you. In order for me to complete them, I require a pair of unadorned leather gloves and three crushed topaz.


**You say:** `legging`




>**Komawin Fe-Dhar says:** The leggings shall protect you, as the valley shelters the still pool within it from the howling winds. Furnish a pair of unadorned leather leggings and three flawed sea sapphires.


**You say:** `boot`




>**Komawin Fe-Dhar says:** Your feet are as hard as any stone and as swift as a coiled serpent but even the swiftest feet require protection so I shall provide you with these. They should help. Acquire a pair of unadorned leather boots and three crushed pieces of black marble.


else 


>**Komawin Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.


end




## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success)

