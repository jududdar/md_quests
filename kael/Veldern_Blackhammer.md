# Veldern Blackhammer



[Veldern Blackhammer](/npc/113162) is a level 30 Giant Warrior that spawns in [Kael Drakkel](/zone/113).



local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(KAEL_ARMOR.Plate_Helmet, 25349), 

quest_helper:melee_chest(KAEL_ARMOR.Breastplate, 25350), 

quest_helper:melee_arms(KAEL_ARMOR.Plate_Vambraces, 25351), 

quest_helper:melee_bracer(KAEL_ARMOR.Plate_Bracer, 25352), 

quest_helper:melee_gloves(KAEL_ARMOR.Plate_Gauntlets, 25353), 

quest_helper:melee_legs(KAEL_ARMOR.Plate_Greaves, 25354), 

quest_helper:melee_boots(KAEL_ARMOR.Plate_Boots, 25355), 
}



## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>*Veldern Blackhammer looks around. 'Who dares address me? Oh, it is a " .. e.other:Race() .. ". Only a shadowknight may address me and proceed further. Are you a shadowknight? Speak, oaf! Otherwise take your prattle elsewhere.'*


**You say:** `shadowknight`




>**Veldern Blackhammer says:** What is it you want little one? Some armor perhaps? To make a pretty meal? I hate when bits of armor get stuck in my gullet. It is very annoying.


**You say:** `some armor`




>*Veldern Blackhammer laughs deeply at you. 'You are so transparent, Soandso. Well, if armor is what you wish, then only the best shall you have for I will not waste my time on nothing less. This is what I will make for you, granted that you can acquire the components for me, a helm, breastplate, armplates, bracers, gauntlets, leggings, and boots.'*


**You say:** `helm`




>**Veldern Blackhammer says:** For the helm I shall require an ancient tarnished plate helmet and three pieces of crushed coral. Does your tiny mind comprehend the task set before you? If so, then get them immediately! I am beginning to get hungry and you are looking all the better as a snack.


**You say:** `breastplate`




>**Veldern Blackhammer says:** For the breastplate, I require this. An ancient tarnished breastplate and three flawless diamonds. Nothing more, nothing less. For perfection, there is a price, insignificant one.


**You say:** `armplate`




>**Veldern Blackhammer says:** For the armplates, I need these components, an ancient tarnished plate vambraces as well as three flawed emeralds. Now go and fetch them before I change my mind.


**You say:** `bracer`




>**Veldern Blackhammer says:** For the bracers, I will require an ancient tarnished plate bracer and three crushed flame emeralds. Now go away before I use your insides as decoration for my boot.


**You say:** `gauntlet`




>**Veldern Blackhammer says:** Your hands are quite important are they not? For without them, you cannot use your precious weapons or shields to protect yourself. You humor me with your feeble attempts. Fetch me an ancient tarnished plate gauntlets and three crushed pieces of topaz for your precious little hands.


**You say:** `legging`




>**Veldern Blackhammer says:** Legs... they are my favorite part of any meal. I like to pull them off first and...Oh, yes, where was I? The leggings. Go and retrieve an ancient tarnished plate greave as well as three flawed sea sapphires. Now, leave my sight before I sample one of yours.


**You say:** `boot`




>**Veldern Blackhammer says:** You wish to have a pair of boots? Then acquire these items for me. A pair of ancient tarnished plate boots and three pieces of crushed black marble. I tire of your prattle. Go away now.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Veldern Blackhammer says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Veldern Blackhammer says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success)