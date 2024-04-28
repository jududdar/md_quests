# Dagron Stonecutter


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(KAEL_ARMOR.Leather_Cap, 25440), 

quest_helper:melee_chest(KAEL_ARMOR.Leather_Tunic, 25441), 

quest_helper:melee_arms(KAEL_ARMOR.Leather_Sleeves, 25442), 

quest_helper:melee_bracer(KAEL_ARMOR.Leather_Bracelet, 25443), 

quest_helper:melee_gloves(KAEL_ARMOR.Leather_Gloves, 25444), 

quest_helper:melee_legs(KAEL_ARMOR.Leather_Leggings, 25445), 

quest_helper:melee_boots(KAEL_ARMOR.Leather_Boots, 25446), 
}

## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Dagron Stonecutter says:** Greetings to you. I seek one who has chosen the path of monkhood. What do you call yourself?


**You say:** `monk`




>**Dagron Stonecutter says:** Good. I had hoped you were one. As seeker of the way you are in constant training to push yourself to your physical and mental limits. It is an admirable quality and I wish to aid you. I will provide you with a cap, a tunic, sleeves, bracers, gloves, leggings and boots.


**You say:** `cap`




>**Dagron Stonecutter says:** I shall weave one of exceptional quality for you but you must gather the items first. I require an ancient leather cap and a set of three pieces of crushed coral.


**You say:** `tunic`




>**Dagron Stonecutter says:** You shall be an imposing force with this tunic. Solid as the unmoving mountains, it shall protect you. Once I have gained an ancient leather tunic and three flawless diamonds, the item is yours.


**You say:** `sleeve`




>**Dagron Stonecutter says:** As the mighty stone that parts the flow of water, so shall these sleeves divert harm against you. Bring me three flawed emeralds and a pair of ancient leather sleeves.


**You say:** `bracer`




>**Dagron Stonecutter says:** For a bracer I shall require an ancient leather bracelet and a set of three crushed flame emeralds. Do this and the reward shall be yours to keep.


**You say:** `glove`




>**Dagron Stonecutter says:** Your hands are like the wind, everflowing and moving. Subtle one moment, then a howling wind raining blow upon blow to your foes. These gloves shall aid you. In order to complete them I require a pair of ancient leather gloves and three crushed topaz.


**You say:** `legging`




>**Dagron Stonecutter says:** The leggings shall protect you, as the valley shelters the still pool within its center from the howling winds. Furnish a pair of ancient leather leggings and a set of three flawed sea sapphires for me and they are yours.


**You say:** `boot`




>**Dagron Stonecutter says:** Your feet are hard as any stone and as swift as a coiled serpent but even the swiftest feet require protection so I shall provide you with these. They should help. Acquire a pair of ancient tarnished boots and three crushed pieces of black marble.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Dagron Stonecutter says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Dagron Stonecutter says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end

## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success) 