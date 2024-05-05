# Terman Underbelly



[Terman Underbelly](/npc/115147) is a level 39 Coldain Shopkeeper that spawns in [The City of Thurgadin](/zone/115).



local quest_helper = require('velious_quest_helper');
local THURG_ARMOR = quest_helper.THURG_ARMOR;

local QUEST_ITEMS = {

quest_helper:priest_helmet(THURG_ARMOR.Chain_Coif, 31007), 

quest_helper:priest_chest(THURG_ARMOR.Chain_Tunic, 31008), 

quest_helper:priest_arms(THURG_ARMOR.Chain_Sleeves, 31009), 

quest_helper:priest_bracer(THURG_ARMOR.Chain_Bracer, 31010), 

quest_helper:priest_gloves(THURG_ARMOR.Chain_Gauntlets, 31011), 

quest_helper:priest_legs(THURG_ARMOR.Chain_Leggings, 31012), 

quest_helper:priest_boots(THURG_ARMOR.Chain_Boots, 31013) 
}



## Dialog

if ( **Faction is** >= Kindly) then


**You say:** `hail`





>*Terman Underbelly speaks in a rumbling tone. 'Greetings. I only wish to speak to a shaman. Are you a shaman?'*


**You say:** `shaman`





>**Terman Underbelly says:** I sense the strength of your mystical powers within you and they vibrate with power.  You have learned much from your travels and I shall help you by providing you with protection from harm and the elements in the form of armor.


**You say:** `armor`





>**Terman Underbelly says:** For you I shall make a coif, tunic, sleeves, bracers, gauntlets, leggings, and boots. Each piece is a quest unto itself. To find the components you must search the lands for them and test the power of the spirit within.


**You say:** `coif`





>**Terman Underbelly says:** Those who are wise as we are know that protection of the head is most important. I may be able to forge you something most interesting if you were to bring me a corroded chain coif and three pieces of crushed onyx sapphire.


**You say:** `tunic`





>**Terman Underbelly says:** If you find a corroded chain tunic and three pieces of black marble bring them to me and I shall attempt to create an enchanted tunic that will serve you well.


**You say:** `sleeve`





>**Terman Underbelly says:** Three jaundice gems and a set of corroded chain sleeves might be an interesting combination. The powers of the gems may be harnessed to imbue the sleeves.


**You say:** `bracer`





>**Terman Underbelly says:** Bracers are quite easy to imbue. Simply find three crushed opals and a corroded chain bracer and I will complete the ritual to enchant them.


**You say:** `gauntlet`






>**Terman Underbelly says:** Strong protection for one's hands is important. I may be able to craft you a set of powerful chain gauntlets if you find a set of corroded chain gauntlets and three crushed lava rubies.


**You say:** `legging`






>**Terman Underbelly says:** Leggings are a bit trickier to imbue. Three chipped onyx sapphires will allow me to channel the correct energies into a pair of corroded chain leggings. However, those chipped onyx sapphires are somewhat rare. Return to me if you find such things in your journeys.


**You say:** `boot`





>**Terman Underbelly says:** Simply bring me a set of three crushed flame emeralds and a pair of corroded chain boots and I will imbue them. I bid you good luck in finding such things.


else


>**Terman Underbelly says:** I do not know you well enough to entrust you with such a quest, yet.
end



## Turn-Ins

quest_helper:quest_turn_in(e, 3, QUEST_ITEMS, quest_helper.thurg_armor_success)