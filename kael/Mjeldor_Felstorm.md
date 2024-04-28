# Mjeldor Felstorm


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:silk_helmet(KAEL_ARMOR.Silk_Turban, 25419),

quest_helper:silk_chest(KAEL_ARMOR.Silk_Robe, 25420),

quest_helper:silk_arms(KAEL_ARMOR.Silk_Sleeves, 25421),

quest_helper:silk_bracer(KAEL_ARMOR.Silk_Wristband, 25422),

quest_helper:silk_gloves(KAEL_ARMOR.Silk_Gloves, 25423),

quest_helper:silk_legs(KAEL_ARMOR.Silk_Pantaloons, 25424),

quest_helper:silk_boots(KAEL_ARMOR.Silk_Boots, 25425),
}

## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Mjeldor Felstorm says:** Greetings to you. I seek those who call themselves magicians. Are you a magician, little one?


**You say:** `magician`




>**Mjeldor Felstorm says:** I thought so. I have several tasks for you to accomplish. Once you have completed them I will have a cap, a robe, sleeves, wristbands, gloves, leggings and boots to reward you with.


**You say:** `cap`




>**Mjeldor Felstorm says:** For you to receive my gift, I shall require an ancient silk turban and three crushed flame opals.


**You say:** `robe`




>**Mjeldor Felstorm says:** This exquisite robe shall be yours in exchange for an ancient silk robe and three pristine emeralds.


**You say:** `sleeve`




>**Mjeldor Felstorm says:** For these durable sleeves, you must fetch me a pair of ancient silk sleeves and three flawed topazes.


**You say:** `wristband`




>**Mjeldor Felstorm says:** The crafting of this wristband requires that you bring me an ancient silk wristband and three crushed pieces of onyx sapphire.


**You say:** `glove`




>**Mjeldor Felstorm says:** For this fine pair of gloves you must seek out and return to me three crushed topazes and a pair of ancient silk gloves.


**You say:** `legging`




>**Mjeldor Felstorm says:** This pair of leggings will be yours provided you supply me with a pair of ancient silk pantaloons as well as three nephrites.


**You say:** `boot`




>**Mjeldor Felstorm says:** These supple boots shall be yours upon receipt of a pair of ancient silk boots and a trilogy of crushed jaundice gems.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Mjeldor Felstorm says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Mjeldor Felstorm says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end

## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success);