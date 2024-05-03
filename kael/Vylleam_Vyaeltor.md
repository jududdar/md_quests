# Vylleam Vyaeltor


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:priest_helmet(KAEL_ARMOR.Plate_Helmet, 25391), 

quest_helper:priest_chest(KAEL_ARMOR.Breastplate, 25392), 

quest_helper:priest_arms(KAEL_ARMOR.Plate_Vambraces, 25393), 

quest_helper:priest_bracer(KAEL_ARMOR.Plate_Bracer, 25394), 

quest_helper:priest_gloves(KAEL_ARMOR.Plate_Gauntlets, 25395), 

quest_helper:priest_legs(KAEL_ARMOR.Plate_Greaves, 25396), 

quest_helper:priest_boots(KAEL_ARMOR.Plate_Boots, 25397), 
}



## Dialog

if( **Faction is** > Warmly) then 


**You say:** `hail`




>*Vylleam Vyaeltor bows 'Greetings to you. You are far away from your homelands, stranger. I am looking for someone. Someone that the outlanders call a cleric. Are you a cleric?'*


**You say:** `cleric`




>**Vylleam Vyaeltor says:** Ahhh... most pious one. I sense the aura of your devotion and conviction and it is strong about you. A shame you are so short lived, mortal. But I see potential in you and for that I shall aid you in your calling. Do you wish my aid?


**You say:** `aid`




>**Vylleam Vyaeltor says:** Then I have a set of goals for you. Once you have achieved them, you shall be rewarded with such as these; a helm, a breastplate, armplates, bracers, gauntlets, greaves and boots. May they protect you from your enemies.


**You say:** `helm`




>**Vylleam Vyaeltor says:** I shall craft a helm for you but you must seek these items out for me first. I have need of an ancient tarnished plate helmet and three crushed onyx sapphires.


**You say:** `breastplate`




>**Vylleam Vyaeltor says:** Such as your faith protects you so shall this breastplate. I must have an ancient tarnished breastplate and three pieces of black marble.


**You say:** `armplate`




>**Vylleam Vyaeltor says:** For the armplates, I shall require a pair of an ancient tarnished plate armplates as well as three jaundice gems. Go forth and seek these out.


**You say:** `bracer`




>**Vylleam Vyaeltor says:** For the bracers, faithful one, I shall require the acquisition of an ancient tarnished plate bracer and three crushed opals.


**You say:** `gauntlet`




>**Vylleam Vyaeltor says:** I will need a pair of a ancient tarnished gauntlets three crushed lava rubys, so that I may make your reward.


**You say:** `greave`




>**Vylleam Vyaeltor says:** You shall acquire a pair of an ancient tarnished plate greaves and three chipped onyx sapphires for me. I await your return.


**You say:** `boot`




>**Vylleam Vyaeltor says:** With your aid I shall make a pair of fine boots for you. All that is needed is a pair of an ancient tarnished plate boots and a trilogy of crushed flame emeralds.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Vylleam Vyaeltor says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Vylleam Vyaeltor says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.

end



## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success) 