# Carver Cagrek

## Dialog

**You say:** `hail`



>**Carver Cagrek says:** Away from carver Cagrek you get!! Me's a busy troll. Must punish enmees of Grobb and feeds trolls a plenty. Trolls complain meats no good, complains dey want sum special bread. Dey says dey hears ogres have special meat which taste better den pris'ners of Grobb. Do you knows name of meat? What kinda [meat] dat be? Tell me!!

**You say:** `fungus dung pie`



>**Carver Cagrek says:** Oh nos! Him wants anudder wun?! Me just maked wun fer him! Yooz gos ta swamp and gets carver Cagrek four spore mushrooms. Be carefuls. Dey easy ta bash, buts sumtimes yooz bash dem too gud and dey falls aparts. Gets me four and me can make pie.

**You say:** `oven mitten`



>**Carver Cagrek says:** Oven mittens?! Whut you need for? You no cook! If you be tinkin you a cook me will gives you oven mittens, but first you brings me tree, not wun or too, but tree froglok meats and also gives me ten gold. You do dis den you get Grobb oven mittens.

**You say:** `hehe meat`



>**Carver Cagrek says:** HEHE meat!! What dat stand for? Mes need some of dis HEHE meat!! Gos and get me some. Cagrek not just want some. Cagrek want more dan twenny!! Cagrek want three HEHE meat and mes want HEHE recipe. You get and me makes Soandso honeraree carver. Me gives you Grobb Cleaver. It cuts skins like dey butter!!
end

## Turn-Ins



local text = "Me needs FOUR spore mushrooms.";

local text1 = "Yous a maroon or what! Me says bring back THREE HEHE meat and HEHE recipe!";

local text2 = "You want oven mittens den you gives me THREE froglok meats and TEN gold.";



if  **You turn in:** [A Spore Mushroom](/item/12191), [A Spore Mushroom](/item/12191), [A Spore Mushroom](/item/12191), [A Spore Mushroom](/item/12191)


>**Carver Cagrek says:** Gud werk! Me already made, err, founds dung part of meal. Here we go. One fungus dung pie! Enjoys.


* __Faction:__ [Da Bashers](/faction/235) (5)


* __Faction:__ [Broken Skull Clan](/faction/222) (-1)


 **You receive:**  [Fungus Spore Pie](/item/12210) (+1000 exp)

elseif  **You turn in:** [Froglok Meat](/item/13409), [Froglok Meat](/item/13409), [Froglok Meat](/item/13409), gold = 10


>**Carver Cagrek says:** Bouts time you gets everyting! Here is you Grobb oven mittens. Dey good to keep you from hot stuff.


* __Faction:__ [Da Bashers](/faction/235) (2)


* __Faction:__ [Broken Skull Clan](/faction/222) (-1)


 **You receive:**  [Grobb Oven Mittens](/item/12211) (+1000 exp)

elseif  **You turn in:** [HEHE Meat](/item/13368), [HEHE Meat](/item/13368), [HEHE Meat](/item/13368), [A Tattered Recipe](/item/18940)


>**Carver Cagrek says:** Finally!! What takes yous so long? Now carver Cagrek try and makes meat and feeds to trolls. Yous getting to be deputy carver. Mes give you Grobb cleaver!! Make strong and smarts on you it will. Just like carver Cagrek.





* __Faction:__ [Da Bashers](/faction/235) (30)


* __Faction:__ [Broken Skull Clan](/faction/222) (-4)


 **You receive:**  [Grobb Cleaver](/item/5413) (+20000 exp)

**This NPC *should* return incorrect items given.**
