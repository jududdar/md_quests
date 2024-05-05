# Fardonad Fe\`Dhar



[Fardonad Fe\`Dhar](/npc/114612) is a level 35 Wyvern Warrior that spawns in [Skyshrine](/zone/114).



local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {
  quest_helper:priest_helmet(SKYSHRINE_ARMOR.Plate_Helmet, 31140), 
  quest_helper:priest_chest(SKYSHRINE_ARMOR.Breastplate, 31141), 
  quest_helper:priest_arms(SKYSHRINE_ARMOR.Plate_Vambraces, 31142), 
  quest_helper:priest_bracer(SKYSHRINE_ARMOR.Plate_Bracer, 31143), 
  quest_helper:priest_gloves(SKYSHRINE_ARMOR.Plate_Gauntlets, 31144), 
  quest_helper:priest_legs(SKYSHRINE_ARMOR.Plate_Greaves, 31145), 
  quest_helper:priest_boots(SKYSHRINE_ARMOR.Plate_Boots, 31146) 
}



## Dialog

if ( **Faction is** > Warmly) then 


**You say:** `hail`




>**Fardonad Fe-Dhar says:** Hail, most pious one. I sense the aura of your devotion and conviction and it is strong about you. A shame you are so short lived, mortal. But I see potential in you and for that I shall aid you in your calling if you are a cleric. Do you wish my aid?


**You say:** `aid`




>**Fardonad Fe-Dhar says:** Then I have a set of goals for you. Once you have achieved them, you shall be rewarded with a helm, a breastplate, armplates, bracers, gauntlets, greaves and boots. May they protect you from your enemies.


**You say:** `helm`




>**Fardonad Fe-Dhar says:** I shall craft a helm for you but you must seek these items out for me first. I have need of an unadorned plate helmet and three pieces of crushed onyx sapphire.


**You say:** `breastplate`




>**Fardonad Fe-Dhar says:** As your faith protects you, so shall this breastplate. I must have an unadorned breastplate and three pieces of black marble.


**You say:** `armplate`




>**Fardonad Fe-Dhar says:** Such lofty goals your kind sets for yourselves. But, that is the way of your kind, I suppose - to seek that which is the most difficult to attain. Bring to me a set of unadorned vambraces and three jaundice gems and you will receive your reward.



**You say:** `bracer`




>**Fardonad Fe-Dhar says:** For the bracers, faithful one, I shall require the acquisition of an unadorned plate bracer as well as three crushed opals.


**You say:** `gauntlet`




>**Fardonad Fe-Dhar says:** I will need a pair of unadorned gauntlets as well as three crushed lava rubies, so that I may make your reward.


**You say:** `greave`




>**Fardonad Fe-Dhar says:** You shall acquire a pair of unadorned plate greaves and three chipped onyx sapphires for me. I await your return.


**You say:** `boot`




>**Fardonad Fe-Dhar says:** With your aid, I shall make a pair of fine boots for you. All that is needed are a pair of unadorned plate boots and three crushed flame emeralds.


else 


>**Fardonad Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success)
end