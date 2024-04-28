# Foreman Felspar

local quest_helper = require('velious_quest_helper');
local THURG_ARMOR = quest_helper.THURG_ARMOR;
local QUEST_TEXT = {

hail="Welcome to the Thurgadin Minin' Company, -name. As foreman it's my job to see that me lads are well trained and well cared fer. Unfortunately, we're not in too good shape right now. Ye see, it seems a new vein was struck recently and a bunch of unwelcome critters have come crawlin outta the works attackin' me lads. In order ta help combat this menace I've engineered a new set of armor for the miners, but need some raw materials to get them started.",

armor="Excellent, -name! I knew ye were the right -race for the job. The pieces I can make are a coif, a tunic, sleeves, bracers, gauntlets, leggings, and boots. This stuff might not be fitting ya if ye're not stealthy like us miners though.",
}

QUEST_TEXT = quest_helper.merge_tables(QUEST_TEXT, quest_helper.THURG_CHAIN_TEXT);

local QUEST_ITEMS = {



quest_helper:melee_boots(THURG_ARMOR.Chain_Boots, 31034),



quest_helper:melee_legs(THURG_ARMOR.Chain_Leggings, 31033),



quest_helper:melee_gloves(THURG_ARMOR.Chain_Gauntlets, 31032),



quest_helper:melee_bracer(THURG_ARMOR.Chain_Bracer, 31031),



quest_helper:melee_arms(THURG_ARMOR.Chain_Sleeves, 31030),



quest_helper:melee_chest(THURG_ARMOR.Chain_Tunic, 31029),



quest_helper:melee_helmet(THURG_ARMOR.Chain_Coif, 31028)
}

## Dialog

quest_helper.quest_text(e, QUEST_TEXT, 3);
## Turn-Ins

quest_helper:quest_turn_in(e, 3, QUEST_ITEMS, quest_helper.thurg_armor_success)