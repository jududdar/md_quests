# Barlek Stonefist


local quest_helper = require('velious_quest_helper');
local KAEL_ARMOR = quest_helper.KAEL_ARMOR;

local QUEST_ITEMS = {

quest_helper:melee_helmet(KAEL_ARMOR.Plate_Helmet, 25370), 

quest_helper:melee_chest(KAEL_ARMOR.Breastplate, 25371), 

quest_helper:melee_arms(KAEL_ARMOR.Plate_Vambraces, 25372), 

quest_helper:melee_bracer(KAEL_ARMOR.Plate_Bracer, 25373), 

quest_helper:melee_gloves(KAEL_ARMOR.Plate_Gauntlets, 25374), 

quest_helper:melee_legs(KAEL_ARMOR.Plate_Greaves, 25375), 

quest_helper:melee_boots(KAEL_ARMOR.Plate_Boots, 25376), 
}

## Dialog

if ( **Faction is** > Warmly) then 


**You say:** `hail`




>**Barlek Stonefist says:** Greetings to you. I seek the service of devout knights who have distinguished themselves. Are you a paladin? If not then be gone.


**You say:** `paladin`




>**Barlek Stonefist says:** A paladin of your order has not made it this far for quite some time. Well, I wonder what it is you seek here. Do you seek heroic and chivalrous deeds to distinguish yourself from your brethren? Do you need accoutrements to aid you in your battles perhaps? You are in luck, knight for I have both for you. Do you wish to partake of my quests?


**You say:** `partake of your quests`




>**Barlek Stonefist says:** Excellent. By serving my cause, you, in turn, will further your own. I require certain components to aid me and if you bring them to me, I shall reward you for your honorable service. You may choose from among these items, a helm, a breastplate, armplates, bracers, gauntlets, greaves, and boots.


**You say:** `helm`




>**Barlek Stonefist says:** All that I require is an ancient tarnished plate helmet and three pieces of crushed coral. This should be a small task for one such as you. Go now and I shall await your return.


**You say:** `breastplate`




>**Barlek Stonefist says:** As the resolve of your faith shall protect you, so shall this breastplate. All that is required is an ancient tarnished breastplate, and three flawless diamonds. Do this quickly so that you may return to your place in the field of battle.


**You say:** `armplates`




>**Barlek Stonefist says:** So, a pair of armplates, is what you require? Well, I require an ancient tarnished plate vambraces as well as three flawed emeralds before you will receive your prize.


**You say:** `bracers`




>**Barlek Stonefist says:** Bracers for the mighty? Retrieve these components and I shall forge the item for you. Bring me an ancient tarnished plate bracelet as well as three crushed flame emeralds.


**You say:** `gauntlets`




>**Barlek Stonefist says:** Mighty gauntlets to smite your foes for the glory of the greater good. It is no easy task but I shall require a pair of an ancient tarnished plate gauntlets and three crushed topaz.


**You say:** `greaves`




>**Barlek Stonefist says:** Sturdy are the pillars that support the temple. I shall make you as strong with these leggings. Gather three flawed sapphires of the sea and a set of ancient tarnished plate greaves.


**You say:** `boots`




>**Barlek Stonefist says:** A pair of boots you shall have once you have gotten a pair of an ancient tarnished plate boots and a set of three crushed pieces of black marble.


elseif ( **Faction is** > Indifferent) then 


**You say:** `hail`




>**Barlek Stonefist says:** We have nothing to talk about small one.


elseif ( **Faction is** <= Indifferent) then


**You say:** `hail`




>**Barlek Stonefist says:** You must prove your dedication to Kael Drakkal and the Kromzek clan before I will speak to you.


## Turn-Ins

quest_helper:quest_turn_in(e, 1, QUEST_ITEMS, quest_helper.kael_armor_success)