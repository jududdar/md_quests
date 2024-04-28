# Abudan Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {

quest_helper:silk_helmet(SKYSHRINE_ARMOR.Silk_Turban, 31161), 

quest_helper:silk_chest(SKYSHRINE_ARMOR.Silk_Robe, 31162), 

quest_helper:silk_arms(SKYSHRINE_ARMOR.Silk_Sleeves, 31163), 

quest_helper:silk_bracer(SKYSHRINE_ARMOR.Silk_Wristband, 31164), 

quest_helper:silk_gloves(SKYSHRINE_ARMOR.Silk_Gloves, 31165), 

quest_helper:silk_legs(SKYSHRINE_ARMOR.Silk_Pantaloons, 31166), 

quest_helper:silk_boots(SKYSHRINE_ARMOR.Silk_Boots, 31167) 
}

## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`



 
>*Abudan Fe-Dhar eyes you malevolently. 'I seek those who practice the dark magicks. I seek those who call themselves necromancers. Are you what I seek?'*


**You say:** `necromancer`




>**Abudan Fe-Dhar says:** Excellent. Are you sure enough of your skills to undertake my tasks? If not, get out of my sight weakling!


**You say:** `task`




>**Abudan Fe-Dhar says:** I thought so. I have several tasks for you accomplish. Once you have completed them I will have a cap, a robe, sleeves, wristbands, gloves, leggings and boots to reward you with.


**You say:** `cap`




>**Abudan Fe-Dhar says:** For you to receive my gift, I shall require three crushed flame opals and a tattered silk turban.


**You say:** `robe`




>**Abudan Fe-Dhar says:** This exquisite robe shall be yours in exchange for a tattered silk robe and three pristine emeralds.


**You say:** `sleeve`




>**Abudan Fe-Dhar says:** For these durable sleeves, you must fetch me a pair of tattered silk sleeves and three flawed topaz.


**You say:** `wristband`




>**Abudan Fe-Dhar says:** The crafting of this wristband requires that you bring me a tattered silk wristband and three crushed onyx sapphires.


**You say:** `glove`




>**Abudan Fe-Dhar says:** For this fine pair of gloves you must seek out and return to me a pair of tattered silk gloves and three crushed topaz.


**You say:** `legging`




>**Abudan Fe-Dhar says:** This pair of leggings will be yours provided you supply me with a pair of tattered silk pantaloons and three nephrite.


**You say:** `boot`




>**Abudan Fe-Dhar says:** These supple boots shall be yours upon receipt of a pair of tattered silk boots and three crushed jaundice gems.


else


>**Abudan Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.



end

## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success) 
