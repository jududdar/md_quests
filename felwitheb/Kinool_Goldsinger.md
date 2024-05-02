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

  

>**Kinool Goldsinger says:** The remaining components are the Trueshot longbow and a treant heart. There will also be the guild donation in the amount of  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/3000" data-url="3000" class="tooltip-link link">Zaharns Coronet</a> gold coins. These and the [fairie gold dust] will merit a ranger the Rain Caller enchanted bow.


local enchant_bars_lib = require("self_found_enchant_bars");

enchant_bars_lib.check_bars_quest_dialogue(e.self, e.other, e.message);
## Turn-Ins



local text = "There will be no Rain Caller until I have the fairie gold dust and the [remaining components].";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18778" data-url="18778" class="tooltip-link link">An Enrollment Letter</a>) then 


>**Kinool Goldsinger says:** Greetings and welcome aboard!  My name's Kinool. Master Enchanter of the Keepers of the Art.  Here is your guild tunic. Make us proud, young pupil!


Your faction standing with [Keepers of the Art](/faction/275) got better (<span class='text-success'>+100</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+25</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+15</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_940.png" alt="" /> <a
                                href="/item/13593" data-url="13593" class="tooltip-link link">Torn Training Robe*</a> (+20 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/12333" data-url="12333" class="tooltip-link link">Pouch of Gold Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/12334" data-url="12334" class="tooltip-link link">a wooden heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1024.png" alt="" /> <a
                                href="/item/8401" data-url="8401" class="tooltip-link link">Trueshot Longbow</a>, gold =  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/3000" data-url="3000" class="tooltip-link link">Zaharns Coronet</a>) then
  

>**Kinool Goldsinger says:** Fine work!! I now reward you with The Rain Caller.


Your faction standing with [Keepers of the Art](/faction/275) got better (<span class='text-success'>+25</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+6</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+3</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-6</span>)
  

 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1024.png" alt="" /> <a
                                href="/item/8402" data-url="8402" class="tooltip-link link">Rain Caller</a> (+5000 exp)

 


local enchant_bars_lib = require("self_found_enchant_bars");


enchant_bars_lib.check_for_bars_to_enchant(item_lib, e.self, e.other, e.trade);


**This NPC *should* return incorrect items given.**
;


