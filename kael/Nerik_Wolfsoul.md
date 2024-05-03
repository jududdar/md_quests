# Nerik Wolfsoul


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(KAEL_ARMOR.Leather_Cap, 5439), 

quest_helper:melee_chest(KAEL_ARMOR.Leather_Tunic, 5440), 

quest_helper:melee_arms(KAEL_ARMOR.Leather_Sleeves, 5441), 

quest_helper:melee_bracer(KAEL_ARMOR.Leather_Bracelet, 5442), 

quest_helper:melee_gloves(KAEL_ARMOR.Leather_Gloves, 5443), 

quest_helper:melee_legs(KAEL_ARMOR.Leather_Leggings, 5444), 

quest_helper:melee_boots(KAEL_ARMOR.Leather_Boots, 5445), 
}



## Dialog

if ( **Faction is** >= Ally) then


**You say:** `hail`





>**Nerik Wolfsoul says:** Greetings to you. I seek one who is known as a beastlord. What do you call yourself, Soandso?



**You say:** `beastlord`





>**Nerik Wolfsoul says:** Then perhaps you would be interested in some armor that I can make you. I can make you a cap, tunic, leggings, bracer, boots, sleeves, and gloves if you bring me the correct items.


**You say:** `cap`





>**Nerik Wolfsoul says:** I shall weave one of exceptional quality for you but you must gather the items first. I require an ancient leather cap and a set of three pieces of crushed coral.


**You say:** `tunic`





>**Nerik Wolfsoul says:** You shall be an imposing force with this tunic. Solid as the unmoving mountains, it shall protect you. Once I have gained an ancient leather tunic and three flawless diamonds, the item is yours.


**You say:** `sleeve`





>**Nerik Wolfsoul says:** As the mighty stone that parts the flow of water, so shall these sleeves divert harm against you. Bring me three flawed emeralds and a pair of ancient leather sleeves.


**You say:** `bracer`





>**Nerik Wolfsoul says:** For a bracer I shall require an ancient leather bracelet and a set of three crushed flame emeralds. Do this and the reward shall be yours to keep.


**You say:** `glove`





>**Nerik Wolfsoul says:** Your hands are like the wind, everflowing and moving. Subtle one moment, then a howling wind raining blow upon blow to your foes. These gloves shall aid you. In order to complete them I require a pair of ancient leather gloves and three crushed topaz.


**You say:** `legging`





>**Nerik Wolfsoul says:** The leggings shall protect you, as the valley shelters the still pool within its center from the howling winds. Furnish a pair of ancient leather leggings and a set of three flawed sea sapphires for me and they are yours.


**You say:** `boot`





>**Nerik Wolfsoul says:** Your feet are hard as any stone and as swift as a coiled serpent but even the swiftest feet require protection so I shall provide you with these. They should help. Acquire a pair of ancient tarnished boots and three crushed pieces of black marble.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Nerik Wolfsoul says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Nerik Wolfsoul says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success) 