# Lorekeeper Zorik



[Lorekeeper Zorik](/npc/115153) is a level 42 Coldain Shopkeeper that spawns in [The City of Thurgadin](/zone/115).



local quest_helper = require('velious_quest_helper');
local THURG_ARMOR = quest_helper.THURG_ARMOR;
local QUEST_TEXT = {

hail="I seek those who practice the art of dark magicks. I seek those who call themselves necromancers. Are you a necromancer?",

necromancer="Excellent. Are you sure enough of your skills to undertake my tasks? If not, get out of my sight, weakling!",

tasks="'I thought so. One should never back down from a challenge. Once you have completed them, I will have a cap, a robe, sleeves, wristbands, gloves, leggings and boots to reward you with.",
}

QUEST_TEXT = quest_helper.merge_tables(QUEST_TEXT, quest_helper.THURG_SILK_TEXT);

local QUEST_ITEMS = {



quest_helper:silk_boots(THURG_ARMOR.Silk_Boots, 31069),



quest_helper:silk_legs(THURG_ARMOR.Silk_Pantaloons, 31068),



quest_helper:silk_gloves(THURG_ARMOR.Silk_Gloves, 31067),



quest_helper:silk_bracer(THURG_ARMOR.Silk_Wristband, 31066),



quest_helper:silk_arms(THURG_ARMOR.Silk_Sleeves, 31065),



quest_helper:silk_chest(THURG_ARMOR.Silk_Robe, 31064),



quest_helper:silk_helmet(THURG_ARMOR.Silk_Turban, 31063)
}



## Dialog

quest_helper.quest_text(e, QUEST_TEXT, 3);


## Turn-Ins

quest_helper:quest_turn_in(e, 3, QUEST_ITEMS, quest_helper.thurg_armor_success)