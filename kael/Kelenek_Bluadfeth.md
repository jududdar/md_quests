# Kelenek Bluadfeth



[Kelenek Bluadfeth](/npc/113157) is a level 30 Giant Warrior that spawns in [Kael Drakkel](/zone/113).



local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(KAEL_ARMOR.Chain_Coif, 25377), 

quest_helper:melee_chest(KAEL_ARMOR.Chain_Tunic, 25378), 

quest_helper:melee_arms(KAEL_ARMOR.Chain_Sleeves, 25379), 

quest_helper:melee_bracer(KAEL_ARMOR.Chain_Bracer, 25380), 

quest_helper:melee_gloves(KAEL_ARMOR.Chain_Gauntlets, 25381), 

quest_helper:melee_legs(KAEL_ARMOR.Chain_Leggings, 25382), 

quest_helper:melee_boots(KAEL_ARMOR.Chain_Boots, 25383), 
}



## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Kelenek Bluadfeth says:** What do we have here? A cutthroat, perhaps? If not then go away, for I have words to speak with a rogue.


**You say:** `rogue`




>**Kelenek Bluadfeth says:** I commend you on your skill, making it this far. I have a job for you, thief. Several in fact and quite simple for an assassin such as yourself. I am in need of certain components and will reward you well if they are brought to me. Do I have your services?


**You say:** `services`




>**Kelenek Bluadfeth says:** Excellent. Now, down to business. I shall pay you in trade for the items I seek. What I have for you is as such, a coif, a breastplate, armplates, bracers, gauntlets, greaves and boots. These should aid you in your skullduggery.


**You say:** `coif`




>**Kelenek Bluadfeth says:** I am need of an ancient tarnished chain coif and three crushed pieces of coral. For your services I shall give you a coif suitable for one such as you.


**You say:** `breastplate`




>**Kelenek Bluadfeth says:** For the breastplate you must seek out an ancient tarnished chain tunic and three flawless diamonds. Only then will you receive a breastplate of my crafting.


**You say:** `armplate`




>**Kelenek Bluadfeth says:** For the armplates I shall give you, I require this; an ancient tarnished chain sleeves and three flawed emeralds.


**You say:** `bracer`




>**Kelenek Bluadfeth says:** An ancient tarnished bracer and three crushed flame emeralds is what I require of you. A bracer of my making is your reward.


**You say:** `gauntlet`




>**Kelenek Bluadfeth says:** I need an ancient tarnished chain gauntlets as well as three crushed topaz. Once I have these you shall have your reward.


**You say:** `greave`




>**Kelenek Bluadfeth says:** A pair of leggings will be your once you completed this task for me, thief. Bring unto me a pair of ancient tarnished chain leggings and a trilogy of flawed sea sapphires.


**You say:** `boot`




>**Kelenek Bluadfeth says:** A fine pair of boots shall you have to skulk around in, once I have a pair of an ancient tarnished chain boots and three pieces of crushed black marble.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Kelenek Bluadfeth says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Kelenek Bluadfeth says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success) 