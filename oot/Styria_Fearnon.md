# Styria Fearnon
## Dialog

**You say:** `hail`



>**Styria Fearnon says:** Welcome to my island. I always welcome visitors, but I would prefer that your stay not last too long. My warriors are sometimes tempted by others. That is why they all wear purity belts. I should warn you, also, to be on the lookout for the [Pirates of Gunthak].

**You say:** `pirates of gunthak`



>**Styria Fearnon says:** The Pirates of Gunthak have been stranded on a nearby island. Their ship was sunk by some unknown water beast. They now attempt to take over this island and commandeer the first ship they encounter. I am looking for brave adventurers to hunt the rogues. Do you wish to hunt the pirates or are you waiting for the next ship?

**You say:** `hunt the pirates`



>**Styria Fearnon says:** Go and seek them out. They are on a nearby island. You will have to swim if you have no boat. Each pirate wears the pirate earring of the Pirates of Gunthak. I shall reward you for each earring you return to me. They have also stolen the Bracers of Erollisi from us. Their leader may have the pair. Return it to me and I shall be very appreciative.

**You say:** `sentry xyrin`



>**Styria Fearnon says:** What? Why are you so concerned for Sentry Xyrin? She returned to Freeport last night right before.. Oh!! Oh, dear!! Right before the storm hit. If she did not make it back to Freeport. I fear she has drowned or is shipwrecked upon one of the nearby islands!! You must find her!


**Spawn NPC:**  [Sentry Xyrin](/npc/69132) at (**y:** -612, **x:** -7332)

**You say:** `purity belt`



>**Styria Fearnon says:** The purity belts were devised with the help of the dwarven smiths. Each warrior of the Sisterhood of Erollisi wears one. It keeps them from impure acts. Only I hold the key.
end

## Turn-Ins




if( **You turn in:** [Bracers of Erollisi](/item/13337)) then 


>**Styria Fearnon says:** Oh!! Thank you!! We are so grateful to you. I offer you this as reward. It is one of the dwarven smith's finest works.





* __Faction:__ [Faydarks Champions](/faction/246) (20)


* __Faction:__ [King Tearis Thex](/faction/279) (5)


* __Faction:__ [Soldiers of Tunare](/faction/310) (5)


* __Faction:__ [Clerics of Tunare](/faction/226) (5)


* __Faction:__ [Crushbone Orcs](/faction/234) (-5)




 **You receive:** eq.ChooseRandom( [Axe](/item/5007), [Broad Sword](/item/5008), [Ringmail Coif](/item/3101), [Iron Visor](/item/3102), [Ringmail Neckguard](/item/3103), [Ringmail Coat](/item/3104), [Ringmail Mantle](/item/3105), [Ringmail Cape](/item/3106), [Ringmail Skirt](/item/3107), [Ringmail Sleeves](/item/3108), [Ringmail Bracelet](/item/3109), [Ringmail Gloves](/item/3110), [Ringmail Pants](/item/3111), [Ringmail Boots](/item/3112)) (+250 exp)

elseif( **You turn in:** [Pirates Earring](/item/13336)) then 


>**Styria Fearnon says:** Good work. That is one less pirate to worry about. We do not have much, but take this as payment.





* __Faction:__ [Faydarks Champions](/faction/246) (5)


* __Faction:__ [King Tearis Thex](/faction/279) (1)


* __Faction:__ [Soldiers of Tunare](/faction/310) (1)


* __Faction:__ [Clerics of Tunare](/faction/226) (1)


* __Faction:__ [Crushbone Orcs](/faction/234) (-1)


 **You receive:** eq.ChooseRandom( [Aviak Feather](/item/13339), [Conch Shell](/item/13342), [Fishing Spear](/item/7017), [Kiola Nut](/item/13340), [Shark Skin](/item/13075)) (+100 exp)

**This NPC *should* return incorrect items given.**
