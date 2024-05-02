# Pandos Flintside
local Bakery = 0;

## Dialog

if(Bakery == 0) then


**You say:** `hail`




>**Pandos Flintside says:** Greetings! Please move along. I am not paid to converse with strangers... unless of course you have a muffin or two..?


**You say:** `brownloe bakery`




>**Pandos Flintside says:** Oh, yes! That is close by. I am sure Lady Shae will be fine for just a minute. I will just run there and run back. Thanks, friend!



eq.start(85); 



**Set a timer** named *Pandos* for 5 seconds



Bakery = 1;

end

## Turn-Ins

local muffin = 0;




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>) then


muffin = 4;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>) then


muffin = 3;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>) then


muffin = 2;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_784.png" alt="" /> <a
                                href="/item/13014" data-url="13014" class="tooltip-link link">Muffin</a>) then


muffin = 1;



if(muffin > 0) then


repeat



>**Pandos Flintside says:** Mmmm. This smells delicious. Oh great!! No milk!! Don't you have any sense?! Just tell me the name of the bakery and I will run and get it myself. I am sure Lady Shae will be safe.



Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+1</span>)



Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+1</span>)



Your faction standing with [Clerics of Tunare](/faction/226) got better (<span class='text-success'>+1</span>)



Your faction standing with [Soldiers of Tunare](/faction/310) got better (<span class='text-success'>+1</span>)



Your faction standing with [Crushbone Orcs](/faction/234) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:** 0 (+5 exp)

 



muffin = muffin - 1;


until muffin == 0

**This NPC *should* return incorrect items given.**

## Timer(s)

local xloc = e.self:GetX();

local yloc = e.self:GetY();


if(xloc == -693 and yloc == -279 and Bakery == 1) then


Bakery = 2;


eq.pause(60);


>**Pandos Flintside says:** I sure could use some of those famous muffins you make!


**Signaled to:**  [Pincia Brownloe](/npc/9088)

elseif(xloc == -497 and yloc == -204 and Bakery == 2) then


eq.stop();


**Stop timer** named *Pandos*


Bakery = 0;
end

## Signals

if(e.signal == 1) then


>**Pandos Flintside says:** Thank you very much! These look delicious. Well, I need to get back to duty. I'll be back tomorrow!


**Signaled to:**  [Pincia Brownloe](/npc/9088)

elseif(e.signal == 2) then


eq.resume();

elseif(e.signal == 3) then


>**Pandos Flintside says:** Yes, Lady Shae.


**Signaled to:**  [Lady Shae](/npc/9058)
end


