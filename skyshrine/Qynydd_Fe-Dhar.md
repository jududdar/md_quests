# Qynydd Fe\`Dhar



[Qynydd Fe\`Dhar](/npc/114624) is a level 35 Wyvern Warrior that spawns in [Skyshrine](/zone/114).



local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {
  quest_helper:priest_helmet(SKYSHRINE_ARMOR.Leather_Cap, 31147), 
  quest_helper:priest_chest(SKYSHRINE_ARMOR.Leather_Tunic, 31148), 
  quest_helper:priest_arms(SKYSHRINE_ARMOR.Leather_Sleeves, 31149), 
  quest_helper:priest_bracer(SKYSHRINE_ARMOR.Leather_Bracelet, 31150), 
  quest_helper:priest_gloves(SKYSHRINE_ARMOR.Leather_Gloves, 31151), 
  quest_helper:priest_legs(SKYSHRINE_ARMOR.Leather_Leggings, 31152), 
  quest_helper:priest_boots(SKYSHRINE_ARMOR.Leather_Boots, 31153), 
}



## Dialog

if ( **Faction is** > Warmly) then 


**You say:** `hail`




>**Qynydd Fe-Dhar says:** Greetings to you. I seek one who calls himself a druid. What do you call yourself, manling?


**You say:** `druid`




>**Qynydd Fe-Dhar says:** Good. I had hoped you were one. As nature's guardian, you fight the never-ending struggle against those who seek to defile it. It is an admirable quality and I wish to aid you. I will provide you with a cap, a tunic, sleeves, bracers, gloves, leggings and boots.


**You say:** `cap`




>**Qynydd Fe-Dhar says:** I shall weave one of exceptional quality for you but you must gather the ingredients first. I require an unadorned leather cap and three crushed onyx sapphires.


**You say:** `tunic`




>**Qynydd Fe-Dhar says:** You shall be a force of nature with this tunic. Once I have gained an unadorned leather tunic and three pieces of black marble, the item is yours.




**You say:** `sleeve`




>**Qynydd Fe-Dhar says:** As the bark protects the limbs of the tree, so shall these sleeves protect your arms. Bring me a pair of unadorned leather sleeves and three jaundice gems.


**You say:** `bracer`




>**Qynydd Fe-Dhar says:** For a bracer I shall require an unadorned leather bracelet as well as three crushed opals. Do this and the reward shall be yours to keep.


**You say:** `glove`




>**Qynydd Fe-Dhar says:** The gloves shall help protect you from the elements and harm. In order for me to complete them, I require a pair of unadorned leather gloves and three crushed lava rubies.


**You say:** `legging`




>**Qynydd Fe-Dhar says:** As the roots support the mighty oak, so shall these leggings support you. Furnish me three chipped onyx sapphires and a pair of unadorned leather leggings.


**You say:** `boot`




>**Qynydd Fe-Dhar says:** Your feet are as hard as any stone and as swift as a coiled serpent but even the swiftest feet require protection so I shall provide you with these. They should help. Acquire a pair of unadorned leather boots and a set of three crushed flame emeralds.


else 


>**Qynydd Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.


end




## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success)

end