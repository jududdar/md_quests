# Crendatha Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(SKYSHRINE_ARMOR.Chain_Coif, 31126), 

quest_helper:melee_chest(SKYSHRINE_ARMOR.Chain_Tunic, 31127), 

quest_helper:melee_arms(SKYSHRINE_ARMOR.Chain_Sleeves, 31128), 

quest_helper:melee_bracer(SKYSHRINE_ARMOR.Chain_Bracer, 31129), 

quest_helper:melee_gloves(SKYSHRINE_ARMOR.Chain_Gauntlets, 31130), 

quest_helper:melee_legs(SKYSHRINE_ARMOR.Chain_Leggings, 31131), 

quest_helper:melee_boots(SKYSHRINE_ARMOR.Chain_Boots, 31132) 
}



## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Crendatha Fe-Dhar says:** What do we have here? A cutthroat, perhaps? If you are a rogue, I may have use for you. I am in need of certain components and will reward you well if they are brought to me. Do I have your services?


**You say:** `service`




>**Crendatha Fe-Dhar says:** Excellent. Now, down to business. I shall pay you in trade for the items I seek. What I have for you is as such, a coif, a breastplate, armplates, bracers, gauntlets, greaves and boots. These should aid you in your skullduggery.


**You say:** `coif`




>**Crendatha Fe-Dhar says:** I am in need of an unadorned chain coif and three crushed pieces of coral. For your services I shall give you a coif suitable for one such as you.


**You say:** `breastplate`




>**Crendatha Fe-Dhar says:** For the breastplate you must seek out an unadorned chain tunic and three flawless diamonds. Only then will you receive a breastplate of my crafting.


**You say:** `armplate`




>**Crendatha Fe-Dhar says:** For the armplates I shall give you, I require these: unadorned chain sleeves and three flawed emeralds.


**You say:** `bracer`




>**Crendatha Fe-Dhar says:** An unadorned bracer and three crushed flame emeralds are what I require of you. A bracer of my making is your reward.


**You say:** `gauntlet`




>**Crendatha Fe-Dhar says:** I need unadorned chain gauntlets and a set of three crushed topaz. Once I have these, you shall have your reward.


**You say:** `legging`




>**Crendatha Fe-Dhar says:** A pair of leggings will be yours once you complete this task for me, thief. A pair of unadorned chain leggings and three flawed sea sapphires are all I require.


**You say:** `boot`




>**Crendatha Fe-Dhar says:** A fine pair of boots shall you have to skulk around in, once you bring me a pair of unadorned chain boots and three pieces of crushed black marble.


else


>**Crendatha Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.
end



## Turn-Ins
  quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success);