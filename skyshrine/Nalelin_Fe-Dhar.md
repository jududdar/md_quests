# Nalelin Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS={

quest_helper:melee_helmet(SKYSHRINE_ARMOR.Chain_Coif, 31112), 

quest_helper:melee_chest(SKYSHRINE_ARMOR.Chain_Tunic, 31113), 

quest_helper:melee_arms(SKYSHRINE_ARMOR.Chain_Sleeves, 31114), 

quest_helper:melee_bracer(SKYSHRINE_ARMOR.Chain_Bracer, 31115), 

quest_helper:melee_gloves(SKYSHRINE_ARMOR.Chain_Gauntlets, 31116), 

quest_helper:melee_legs(SKYSHRINE_ARMOR.Chain_Leggings, 31117), 

quest_helper:melee_boots(SKYSHRINE_ARMOR.Chain_Boots, 31118), 
}

## Dialog

if ( **Faction is** > Warmly) then 


**You say:** `hail`




>**Nalelin Fe-Dhar says:** Greetings, I seek the ones who stalk through the forests protecting it. If you are one known as a ranger, submit to my will and become stronger. The tasks I set forth will not be easy. Are you ready to submit to my will?


**You say:** `submit`




>**Nalelin Fe-Dhar says:** That is good, for there is nothing like the wrath of nature, woodland warrior. And Nature's wrath shall you be, with this armor to protect you in your struggle. I shall forge a coif, breastplate, sleeves, bracers, gauntlets, leggings, and boots for you.


**You say:** `coif`




>**Nalelin Fe-Dhar says:** This coif shall protect you from battle and the elements. What I require of you are these: an unadorned chain coif and three pieces of crushed coral. Do not waste precious time!


**You say:** `breastplate`




>**Nalelin Fe-Dhar says:** Even as the hardest tree in the forest gains protection from its bark, so shall you gain the protection of this breastplate. Bring these components for me - an unadorned chain tunic and three flawless diamonds.


**You say:** `sleeve`




>**Nalelin Fe-Dhar says:** I require unadorned chain sleeves, as well as three flawed emeralds. Do this so that I may grant you them as a gift for your diligence.





**You say:** `bracer`




>**Nalelin Fe-Dhar says:** This shall help shield your forearms from any stray blows. Bring me an unadorned chain bracelet and three crushed flame emeralds.


**You say:** `gauntlet`




>**Nalelin Fe-Dhar says:** Bring me these items, for I will not grant you your pair until then - a pair of unadorned chain gauntlets and a set of three crushed topaz.


**You say:** `legging`




>**Nalelin Fe-Dhar says:** A pair of leggings you seek? I seek something as well. Bring me a pair of unadorned chain leggings and three flawed sea sapphires. Go now. The struggle continues as we speak.


**You say:** `boot`




>**Nalelin Fe-Dhar says:** For the boots, I shall require a pair of unadorned chain boots as well as three pieces of crushed black marble.


else 


>**Nalelin Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.






## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success);