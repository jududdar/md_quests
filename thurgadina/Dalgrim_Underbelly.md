# Dalgrim Underbelly



[Dalgrim Underbelly](/npc/115146) is a level 42 Coldain Shopkeeper that spawns in [The City of Thurgadin](/zone/115).



local quest_helper = require('velious_quest_helper');
local THURG_ARMOR = quest_helper.THURG_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(THURG_ARMOR.Plate_Helmet, 31000), 

quest_helper:melee_chest(THURG_ARMOR.Breastplate, 31001), 

quest_helper:melee_arms(THURG_ARMOR.Plate_Vambraces, 31002), 

quest_helper:melee_bracer(THURG_ARMOR.Plate_Bracer, 31003), 

quest_helper:melee_gloves(THURG_ARMOR.Plate_Gauntlets, 31004), 

quest_helper:melee_legs(THURG_ARMOR.Plate_Greaves, 31005), 

quest_helper:melee_boots(THURG_ARMOR.Plate_Boots, 31006), 
}



## Dialog

if( **Faction is** >= Kindly) then


**You say:** `hail`





>**Dalgrim Underbelly says:** I wasn't always just a merchant, ye know, I used to work at the temple and spent most of my time in the study of ancient texts and arts. I actually learned a lot about the dark arts in those days. Ye know... necromancy. Oh, I'd never touch the stuff, mind ye, but I'll bet I could make a fine set of plate fer shadowknights if'n I had the right materials.


**You say:** `material`





>**Dalgrim Underbelly says:** Glad to see ye're interested, Soandso. The materials would vary by the piece of armor o' course. I could probably forge a fine set of bracers, gauntlets, greaves, boots, armplates, a helm, or a breastplate.


**You say:** `helm`





>**Dalgrim Underbelly says:** To create a piece of armor to protect your skull I will require three pieces of crushed coral as well as a corroded plate helmet.


**You say:** `breastplate`





>**Dalgrim Underbelly says:** For the breastplate, I will need a corroded breastplate and three flawless diamonds. Once I have them in my possession it will not take long to craft a sturdy breastplate.


**You say:** `armplates`





>**Dalgrim Underbelly says:** Protection for your arms will come at the price of a set of corroded plate vambraces and three flawed emeralds.


**You say:** `bracers`





>**Dalgrim Underbelly says:** For the bracers, I will require a corroded plate bracer and a set of three crushed flame emeralds. Return to me if you happen to find these things in your travels.


**You say:** `gauntlets`





>**Dalgrim Underbelly says:** Protecting your hands is very important. I can forge protection for your hands if you bring me a pair of corroded plate gauntlets and three crushed topaz.


**You say:** `greaves`





>**Dalgrim Underbelly says:** A set of corroded greaves might be salvageable if you were to find three flawed sea sapphires. With the right techniques almost anything is possible.


**You say:** `boots`





>**Dalgrim Underbelly says:** Boots made for battle are not always the most comfortable available. However, if you seek a fine set for battle bring me a set of corroded plate boots and three pieces of crushed black marble.


else


>**Dalgrim Underbelly says:** I do not know you well enough to entrust you with such a quest, yet.
end



## Turn-Ins

quest_helper:quest_turn_in(e, 3, QUEST_ITEMS, quest_helper.thurg_armor_success);