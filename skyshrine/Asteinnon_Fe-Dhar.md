# Asteinnon Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {
  quest_helper:priest_helmet(SKYSHRINE_ARMOR.Chain_Coif, 31105), 
  quest_helper:priest_chest(SKYSHRINE_ARMOR.Chain_Tunic, 31106), 
  quest_helper:priest_arms(SKYSHRINE_ARMOR.Chain_Sleeves, 31107), 
  quest_helper:priest_bracer(SKYSHRINE_ARMOR.Chain_Bracer, 31108), 
  quest_helper:priest_gloves(SKYSHRINE_ARMOR.Chain_Gauntlets, 31109), 
  quest_helper:priest_legs(SKYSHRINE_ARMOR.Chain_Leggings, 31110), 
  quest_helper:priest_boots(SKYSHRINE_ARMOR.Chain_Boots, 31111) 
}

## Dialog
  if ( **Faction is** > Warmly) then 

**You say:** `hail`


  >*Asteinnon Fe-Dhar speaks in a deep tone, 'Greetings. I wish to speak only to a shaman, so I might aid them with protection from the world in the form of armor.'*

**You say:** `armor`


>**Asteinnon Fe-Dhar says:** For you I shall make a coif, breastplate, sleeves, bracers, gauntlets, leggings, and boots. Each piece is a quest unto itself. To seek the components, you must search the lands for them and test the power of the spirit within.

**You say:** `coif`


>**Asteinnon Fe-Dhar says:** The coif I shall make will be comprised of an unadorned chain coif and three crushed onyx sapphires. I shall be waiting.

**You say:** `breastplate`


>**Asteinnon Fe-Dhar says:** A breastplate to protect the spirit within. I shall make one for you granted that you retrieve the components I shall need. An unadorned chain tunic and three pieces of black marble. I await your return.

**You say:** `sleeve`


>**Asteinnon Fe-Dhar says:** Sleeves I shall make upon receipt of unadorned chain sleeves and a set of three jaundice gems. Complete this simple task and they are yours.

**You say:** `bracer`


>**Asteinnon Fe-Dhar says:** A bracer of mystic power I shall grant you. All I require is the acquisition of an unadorned chain bracer and three crushed opals.

**You say:** `gauntlet`


>**Asteinnon Fe-Dhar says:** I shall require three crushed lava rubies and an unadorned pair of chain gauntlets to complete my ritual.

**You say:** `legging`


>**Asteinnon Fe-Dhar says:** You seek leggings? Then provide for me unadorned chain leggings and three chipped onyx sapphires and I will give them to you for your service.

**You say:** `boot`


>**Asteinnon Fe-Dhar says:** These boots will help you in your never-ending quest. I shall grant them upon receipt of a pair of unadorned chain boots and three crushed flame emeralds.
  else

>**Asteinnon Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.
 end

## Turn-Ins
  quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success)