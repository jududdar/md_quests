# Bygloirn Omorden



[Bygloirn Omorden](/npc/113183) is a level 30 Giant Warrior that spawns in [Kael Drakkel](/zone/113).



local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(KAEL_ARMOR.Plate_Helmet, 25384), 

quest_helper:melee_chest(KAEL_ARMOR.Breastplate, 25385), 

quest_helper:melee_arms(KAEL_ARMOR.Plate_Vambraces, 25386), 

quest_helper:melee_bracer(KAEL_ARMOR.Plate_Bracer, 25387), 

quest_helper:melee_gloves(KAEL_ARMOR.Plate_Gauntlets, 25388), 

quest_helper:melee_legs(KAEL_ARMOR.Plate_Greaves, 25389), 

quest_helper:melee_boots(KAEL_ARMOR.Plate_Boots, 25390), 
}



## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>**Bygloirn Omorden says:** Hail! I long to speak with a minstrel. I am curious about what has gone on beyond our borders here. Are you a bard? If not then I have no use for you.


**You say:** `bard`




>**Bygloirn Omorden says:** So troubadour, what news and stories have you from the New World? Oh, I forget my manners. We shall exchange talk another time. You seek something do you not? A new outfit perhaps?


**You say:** `new outfit`




>**Bygloirn Omorden says:** Well then, I have just what you need. Now, my terms of payment is thus, you gather some things for me and in return I shall craft you the finest armor a bard has ever seen! A new outfit comprised of a helm, breastplate, armplates, bracers, gauntlets, greaves, and boots shall make you the envy of your peers, my little friend.


**You say:** `helm`




>**Bygloirn Omorden says:** A brand new shiny helm shall be yours once I have an ancient tarnished plate helmet and three pieces of crushed coral. May the audience swoon in your presence.


**You say:** `breastplate`




>**Bygloirn Omorden says:** I have need of an ancient tarnished breastplate and three flawless diamonds. Find these for me and I shall craft you a breastplate, minstrel. May it protect you from unruly audiences with rotten vegetables.


**You say:** `armplate`




>**Bygloirn Omorden says:** A gorgeous pair of armplates shall be yours once you have retrieved a pair of ancient tarnished plate vambraces and three flawed emeralds. The detail and craftsmanship is stunning!


**You say:** `bracer`




>**Bygloirn Omorden says:** A pair of bracers shall be yours upon receipt of an ancient tarnished plate bracer and three crushed flame emeralds. May your songs never falter during a tactical retreat.


**You say:** `gauntlet`




>**Bygloirn Omorden says:** It would be a shame if your hands were to be injured and not be able to play your instruments wouldn't it? I shall craft some gauntlets so that your nimble digits remain intact. Bring me a pair of ancient tarnished plate gauntlets as well as three crushed topaz.


**You say:** `greave`




>**Bygloirn Omorden says:** Some new greaves would do you some good. The pair you have now looks quite stained and worn. Nevermind, fetch me a pair of ancient tarnished plate greaves and three flawed sea sapphires.


**You say:** `boot`




>**Bygloirn Omorden says:** A fancy pair of boots you want is it? Yes, I can see the pair you have now looks a bit worn from running so much. All I require is a set of three crushed pieces of black marble and a pair of ancient tarnished plate boots.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Bygloirn Omorden says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Bygloirn Omorden says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success) 