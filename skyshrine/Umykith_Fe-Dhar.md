# Umykith Fe-Dhar


local quest_helper = require('velious_quest_helper');
local SKYSHRINE_ARMOR = quest_helper.SKYSHRINE_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(SKYSHRINE_ARMOR.Plate_Helmet, 31133), 

quest_helper:melee_chest(SKYSHRINE_ARMOR.Breastplate, 31134), 

quest_helper:melee_arms(SKYSHRINE_ARMOR.Plate_Vambraces, 31135), 

quest_helper:melee_bracer(SKYSHRINE_ARMOR.Plate_Bracer, 31136), 

quest_helper:melee_gloves(SKYSHRINE_ARMOR.Plate_Gauntlets, 31137), 

quest_helper:melee_legs(SKYSHRINE_ARMOR.Plate_Greaves, 31138), 

quest_helper:melee_boots(SKYSHRINE_ARMOR.Plate_Boots, 31139), 
}



## Dialog

if( **Faction is** >= Ally ) then 


**You say:** `hail`




>**Umykith Fe-Dhar says:** Hail! What news and stories have you from the New World? Perhaps if you are a bard you can spin me stories of those lands. Oh, I forget my manners. We shall exchange talk another time. You seek something, do you not? A new outfit perhaps?


**You say:** `outfit`




>**Umykith Fe-Dhar says:** Well, then I have just what you need. Now, my terms of payment are thus, you gather some things for me and in return I shall craft you the finest armor a bard has ever seen! A new outfit comprised of a helm, breastplate, armplates, bracers, gauntlets, greaves, and boots shall make you the envy of your peers, my little friend.


**You say:** `helm`




>**Umykith Fe-Dhar says:** A brand new shiny helm shall be yours once I have an unadorned plate helmet and three pieces of crushed coral. May the audience swoon in your presence.


**You say:** `breastplate`




>**Umykith Fe-Dhar says:** For the breastplate, I require an unadorned breastplate and three flawless diamonds. Nothing more, nothing less. For perfection, there is a price, insignificant one.


**You say:** `armplate`




>**Umykith Fe-Dhar says:** For the armplates, I need these components - unadorned plate vambraces as well as three flawed emeralds. Now go and fetch them before I change my mind.


**You say:** `bracer`



>**Umykith Fe-Dhar says:** A pair of bracers shall be yours upon receipt of an unadorned plate bracer and three crushed flame emeralds. May your songs never falter during a tactical retreat.


**You say:** `gauntlet`




>**Umykith Fe-Dhar says:** It would be a shame if your hands were to be injured wouldn't it? I shall craft some gauntlets so that your nimble digits remain intact. Bring me a pair of unadorned plate gauntlets as well as three crushed topaz.


**You say:** `greave`




>**Umykith Fe-Dhar says:** Some new greaves would do you some good. The pair you have now looks quite stained and worn. Fetch me a pair of unadorned plate greaves and three flawed sea sapphires.


**You say:** `boot`




>**Umykith Fe-Dhar says:** You wish to have a pair of boots? Then acquire these items for me. Three pieces of crushed black marble and a pair of unadorned plate boots. I tire of your prattle. Go away now.



else 


>**Umykith Fe-Dhar says:** You must prove your dedication to the Claws of Veeshan before I will speak to you.
end



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.skyshrine_armor_success) 