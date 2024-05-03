# Jaglorm Ygorr


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:priest_helmet(KAEL_ARMOR.Leather_Cap, 25398), 

quest_helper:priest_chest(KAEL_ARMOR.Leather_Tunic, 25399), 

quest_helper:priest_arms(KAEL_ARMOR.Leather_Sleeves, 25400), 

quest_helper:priest_bracer(KAEL_ARMOR.Leather_Bracelet, 25401), 

quest_helper:priest_gloves(KAEL_ARMOR.Leather_Gloves, 25402), 

quest_helper:priest_legs(KAEL_ARMOR.Leather_Leggings, 25403), 

quest_helper:priest_boots(KAEL_ARMOR.Leather_Boots, 25404), 
}



## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Jaglorm Ygorr says:** Greetings to you. I seek one that calls himself a druid. What do you call yourself, manling?


**You say:** `druid`




>**Jaglorm Ygorr says:** Good. I had hoped you were one. As nature's guardian, you fight the never-ending struggle against those who seek to defile it. It is an admirable quality and I wish to aid you. I will provide you with a cap, a tunic, sleeves, bracers, gloves, leggings and boots.


**You say:** `cap`




>**Jaglorm Ygorr says:** I shall weave one of exceptional quality for you but you must gather the ingredients first. I require an ancient leather cap and three crushed onyx sapphires.


**You say:** `tunic`




>**Jaglorm Ygorr says:** You shall be a force of nature with this tunic. Once I have gained an ancient leather tunic and three pieces of black marble the item is yours.


**You say:** `sleeve`




>**Jaglorm Ygorr says:** As the bark protects the limbs of the tree, so shall these sleeves protect your arms. Bring me a pair of an ancient leather sleeves and three jaundice gems.


**You say:** `bracer`




>**Jaglorm Ygorr says:** For a bracer I shall require an ancient leather bracelet, and three crushed opals. Do this and the reward shall be yours to keep.


**You say:** `glove`




>**Jaglorm Ygorr says:** The gloves shall help protect you from the elements and harm. In order for me to complete them I require a pair of an ancient leather gloves and three crushed lava rubys.


**You say:** `legging`




>**Jaglorm Ygorr says:** As the roots support the mighty oak, so shall these leggings support you. Furnish a pair of an ancient leather leggings as well as three chipped onyx sapphires and they are yours.


**You say:** `boot`




>**Jaglorm Ygorr says:** Even the swiftest feet need protection so I shall provide you with these. They should help. Acquire a pair of ancient boots and three crushed flame emeralds.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Jaglorm Ygorr says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Jaglorm Ygorr says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success) 