# Ulkar Jollkarek


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:silk_helmet(KAEL_ARMOR.Silk_Turban, 25405),

quest_helper:silk_chest(KAEL_ARMOR.Silk_Robe, 25406),

quest_helper:silk_arms(KAEL_ARMOR.Silk_Sleeves, 25407),

quest_helper:silk_bracer(KAEL_ARMOR.Silk_Wristband, 25408),

quest_helper:silk_gloves(KAEL_ARMOR.Silk_Gloves, 25409),

quest_helper:silk_legs(KAEL_ARMOR.Silk_Pantaloons, 25410),

quest_helper:silk_boots(KAEL_ARMOR.Silk_Boots, 25411),
}

## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Ulkar Jollkarek says:** Greetings to you. I seek one that calls himself a wizard. What do you call yourself, manling?


**You say:** `wizard`




>**Ulkar Jollkarek says:** Excellent. Are you sure enough of your skills to undertake my tasks? If not, get out of my sight, weakling!


**You say:** `task`




>**Ulkar Jollkarek says:** I thought so. One should never back down from a challenge. Once you have completed them I will have a cap, a robe, sleeves, wristbands, gloves, leggings and boots to reward you with.


**You say:** `cap`




>**Ulkar Jollkarek says:** For you to receive my gift, I shall require an ancient silk turban and three crushed flame opals.


**You say:** `robe`




>**Ulkar Jollkarek says:** This exquisite robe shall be yours in exchange for an ancient silk robe and three pristine emeralds.


**You say:** `sleeve`




>**Ulkar Jollkarek says:** For these durable sleeves, you must fetch me a pair of ancient silk sleeves and three flawed topazes.


**You say:** `wristband`




>**Ulkar Jollkarek says:** The crafting of this wristband requires that you bring me an ancient silk wristband and three crushed pieces of onyx sapphire.


**You say:** `glove`




>**Ulkar Jollkarek says:** For this fine pair of gloves you must seek out and return to me three crushed topazes and a pair of ancient silk gloves.


**You say:** `legging`




>**Ulkar Jollkarek says:** This pair of leggings will be yours provided you supply me with a pair of ancient silk pantaloons as well as three nephrites.


**You say:** `boot`




>**Ulkar Jollkarek says:** These supple boots shall be yours upon receipt of a pair of ancient silk boots and a trilogy of crushed jaundice gems.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Ulkar Jollkarek says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Ulkar Jollkarek says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end

## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success);
