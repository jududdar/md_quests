# Kinool Goldsinger
## Dialog

**You say:** `hail`



>**Kinool Goldsinger says:** Hail and welcome.  I am sure you have much to do, but could I ask a [favor] of you?

**You say:** `favor`



>**Kinool Goldsinger says:** Oh, um, on second thought, never mind.  I should really just do it myself.  Thank you anyway.

**You say:** `enchanted bow`

  

>**Kinool Goldsinger says:** Alas... Another ranger in search of the [Rain Caller]. She is no more

**You say:** `rain caller`

  

>**Kinool Goldsinger says:** Rain Caller is the name we give each Trueshot longbow once it is enchanted. Unfortunately, I am unable to enchant them any longer. One of the components is no longer available. Someone would have to strike a [deal with the fairie folk]. Once I have that and the [remaining components] I can create the Rain Caller, a ranger's bow

**You say:** `fairie folk`

  

>**Kinool Goldsinger says:** The fairie princess, Joleena, used to have a metal gnome deliver [fairie gold dust] to the Keepers every month. She has stopped this and now refuses to offer it to any nation of Faydwer. What she is angry about, we do not know.

**You say:** `gold dust`

 
 
>**Kinool Goldsinger says:** Fairie gold dust is an enchanted powder which only a fairie princess can create.

**You say:** `remaining component`

  

>**Kinool Goldsinger says:** The remaining components are the Trueshot longbow and a treant heart. There will also be the guild donation in the amount of  [Zaharns Coronet](/item/3000) gold coins. These and the [fairie gold dust] will merit a ranger the Rain Caller enchanted bow.


local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_bars_quest_dialogue(e.self, e.other, e.message);
## Turn-Ins



local text = "There will be no Rain Caller until I have the fairie gold dust and the [remaining components].";


if( **You turn in:** [An Enrollment Letter](/item/18778)) then 


>**Kinool Goldsinger says:** Greetings and welcome aboard!  My name's Kinool. Master Enchanter of the Keepers of the Art.  Here is your guild tunic. Make us proud, young pupil!


* __Faction:__ [Keepers of the Art](/faction/275) (100)


* __Faction:__ [King Tearis Thex](/faction/279) (25)


* __Faction:__ [Faydarks Champions](/faction/246) (15)


* __Faction:__ [The Dead](/faction/239) (-25)


 **You receive:**  [Torn Training Robe*](/item/13593) (+20 exp)

elseif( **You turn in:** [Pouch of Gold Dust](/item/12333), [a wooden heart](/item/12334), [Trueshot Longbow](/item/8401), gold =  [Zaharns Coronet](/item/3000)) then
  

>**Kinool Goldsinger says:** Fine work!! I now reward you with The Rain Caller.


* __Faction:__ [Keepers of the Art](/faction/275) (25)


* __Faction:__ [King Tearis Thex](/faction/279) (6)


* __Faction:__ [Faydarks Champions](/faction/246) (3)


* __Faction:__ [The Dead](/faction/239) (-6)
  

 **You receive:**  [Rain Caller](/item/8402) (+5000 exp)


local enchant_bars_lib = require("self_found_enchant_bars");


enchant_bars_lib.check_for_bars_to_enchant(item_lib, e.self, e.other, e.trade);


**This NPC *should* return incorrect items given.**
;


