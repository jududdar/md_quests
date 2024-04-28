# Lorekeeper Brita


local quest_helper = require('velious_quest_helper');
local THURG_ARMOR = quest_helper.THURG_ARMOR;

## Dialog

if( **Faction is** >= Kindly ) then 


**You say:** `hail`




>**Lorekeeper Brita says:** Greetings to you.  I seek those who call themselves enchanters.  Are you an enchanter?


**You say:** `enchanter`




>**Lorekeeper Brita says:** I thought so.  I have several tasks for you accomplish.  Once you have completed them I will have a cap, a robe, sleeves, wristbands, gloves, leggings and boots to reward you with.
 

**You say:** `cap`




>**Lorekeeper Brita says:** For an enchanted head guard bring me a torn enchanted silk turban as well as three pieces of crushed flame opal.
 

**You say:** `robe`




>**Lorekeeper Brita says:** With three pristine emeralds and a torn enchanted silk robe I will fashion a wonderous robe for you.


**You say:** `sleeve`




>**Lorekeeper Brita says:** Bring unto me a set of torn enchanted silk sleeves as well as three flawed topaz.  With these in my possession I can create a set of enchanted sleeves the likes of which spellcasters like you dream of.


**You say:** `wristband`




>**Lorekeeper Brita says:** An enchanted silk wristguard and three crushed onyx sapphires is all that I require to create an imbued wrist wrap of great power.  Seek out these items and return to me when you have acquired them.


**You say:** `legging`




>**Lorekeeper Brita says:** Three nephrite and a pair of torn enchanted silk leggings will net you a fine set of pantaloons.


**You say:** `boot`




>**Lorekeeper Brita says:** Three crushed jaundice gems combined with torn enchanted silk boots would make a most interesting set of footwear.  The latent powers of the gems can be harnessed to create magical effects.


**You say:** `glove`




>**Lorekeeper Brita says:** If you seek gloves of great power, bring to me three crushed topaz and a pair of torn enchanted silk gloves.  I will use the power of the gems to imbue the gloves.


else


>**Lorekeeper Brita says:** I do not know you well enough to entrust you with such a quest, yet.
end

local QUEST_ITEMS = {



quest_helper:silk_boots(THURG_ARMOR.Silk_Boots, 31083),



quest_helper:silk_legs(THURG_ARMOR.Silk_Pantaloons, 31082),



quest_helper:silk_gloves(THURG_ARMOR.Silk_Gloves, 31081),



quest_helper:silk_bracer(THURG_ARMOR.Silk_Wristband, 31080),



quest_helper:silk_arms(THURG_ARMOR.Silk_Sleeves, 31079),



quest_helper:silk_chest(THURG_ARMOR.Silk_Robe, 31078),



quest_helper:silk_helmet(THURG_ARMOR.Silk_Turban, 31077),
}

## Turn-Ins


local item_lib = require('items');


if  **You turn in:** [Ulthork Meat Pie](/item/1427), [Britas Napkin](/item/1417)


>**Lorekeeper Brita says:** Ohh, that's better. I get so touchy when I'm hungry. I should probably go apologize to Derrin for being snappy. Please return this to Mordin for me.


* __Faction:__ [Coldain](/faction/406) (3)


* __Faction:__ [Dain Frostreaver IV](/faction/405) (1)


* __Faction:__ [Kromrif](/faction/419) (-1)


* __Faction:__ [Kromzek](/faction/448) (-1)


 **You receive:**  [Used Pie Tin](/item/1424) 

quest_helper:quest_turn_in(e, 3, QUEST_ITEMS, quest_helper.thurg_armor_success)