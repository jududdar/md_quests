# Elaend Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {

quest_helper:silk_helmet(SKYSHRINE_ARMOR.Silk_Turban, 31154), 

quest_helper:silk_chest(SKYSHRINE_ARMOR.Silk_Robe, 31155), 

quest_helper:silk_arms(SKYSHRINE_ARMOR.Silk_Sleeves, 31156), 

quest_helper:silk_bracer(SKYSHRINE_ARMOR.Silk_Wristband, 31157), 

quest_helper:silk_gloves(SKYSHRINE_ARMOR.Silk_Gloves, 31158), 

quest_helper:silk_legs(SKYSHRINE_ARMOR.Silk_Pantaloons, 31159), 

quest_helper:silk_boots(SKYSHRINE_ARMOR.Silk_Boots, 31160) 
}



## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Elaend Fe-Dhar says:** Greetings to you. I seek one who calls himself a wizard. What do you call yourself, manling?


**You say:** `wizard`




>**Elaend Fe-Dhar says:** Excellent. Are you sure enough of your skills to undertake my tasks? If not, get out of my sight!


**You say:** `task`




>**Elaend Fe-Dhar says:** I thought so. One should never back down from a challenge. Once you have completed them I will have a cap, a robe, sleeves, wristbands, gloves, leggings and boots.


**You say:** `cap`




>**Elaend Fe-Dhar says:** For you to receive my gift, I shall require three crushed flame opals and a tattered silk turban.


**You say:** `robe`




>**Elaend Fe-Dhar says:** This exquisite robe shall be yours in exchange for a tattered silk robe and three pristine emeralds.


**You say:** `sleeve`




>**Elaend Fe-Dhar says:** For these durable sleeves, you must fetch me a pair of tattered silk sleeves and three flawed topaz.


**You say:** `wristband`




>**Elaend Fe-Dhar says:** The crafting of this wristband requires that you bring me a tattered silk wristband and three crushed onyx sapphires.


**You say:** `glove`




>**Elaend Fe-Dhar says:** For this fine pair of gloves you must seek out and return to me a pair of tattered silk gloves and three crushed topaz.


**You say:** `legging`




>**Elaend Fe-Dhar says:** This pair of leggings will be yours provided you supply me with a pair of tattered silk pantaloons and three nephrite.


**You say:** `boot`




>**Elaend Fe-Dhar says:** These supple boots shall be yours upon receipt of a pair of tattered silk boots and three crushed jaundice gems.


else 


>**Elaend Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.
end



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success);
end