# Bjarorm Mjlorn


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:silk_helmet(KAEL_ARMOR.Silk_Turban, 25412),

quest_helper:silk_chest(KAEL_ARMOR.Silk_Robe, 25413),

quest_helper:silk_arms(KAEL_ARMOR.Silk_Sleeves, 25414),

quest_helper:silk_bracer(KAEL_ARMOR.Silk_Wristband, 25415),

quest_helper:silk_gloves(KAEL_ARMOR.Silk_Gloves, 25416),

quest_helper:silk_legs(KAEL_ARMOR.Silk_Pantaloons, 25417),

quest_helper:silk_boots(KAEL_ARMOR.Silk_Boots, 25418),
}

## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Bjarorm Mjlorn says:** I seek those who practice the dark magicks. I seek those who call themselves necromancers. Are you a necromancer?


**You say:** `necromancer`




>**Bjarorm Mjlorn says:** Excellent. Are you sure enough of your skills to undertake my tasks? If not, get out of my sight, weakling!


**You say:** `task`




>**Bjarorm Mjlorn says:** I thought so. One should never back down from a challenge. Once you have completed them I will have a cap, a robe, sleeves, wristbands, gloves, leggings and boots to reward you with.


**You say:** `cap`




>**Bjarorm Mjlorn says:** For you to receive my gift, I shall require an ancient silk turban and three crushed flame opals.


**You say:** `robe`




>**Bjarorm Mjlorn says:** This exquisite robe shall be yours in exchange for an ancient silk robe and three pristine emeralds.


**You say:** `sleeve`




>**Bjarorm Mjlorn says:** For these durable sleeves, you must fetch me a pair of ancient silk sleeves and three flawed topazes.


**You say:** `wristband`




>**Bjarorm Mjlorn says:** The crafting of this wristband requires that you bring me an ancient silk wristband and three crushed pieces of onyx sapphire.


**You say:** `glove`




>**Bjarorm Mjlorn says:** For this fine pair of gloves you must seek out and return to me a pair of ancient silk gloves and a crushed topaz.


**You say:** `legging`




>**Bjarorm Mjlorn says:** This pair of leggings will be yours provided you supply me with a pair of ancient silk pantaloons as well as three nephrites.


**You say:** `boot`




>**Bjarorm Mjlorn says:** These supple boots shall be yours upon receipt of a pair of ancient silk boots and a trilogy of crushed jaundice gems.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Bjarorm Mjlorn says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Bjarorm Mjlorn says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end

## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success);