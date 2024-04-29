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




if( **You turn in:** [Muffin](/item/13014), [Muffin](/item/13014), [Muffin](/item/13014), [Muffin](/item/13014)) then


muffin = 4;

elseif( **You turn in:** [Muffin](/item/13014), [Muffin](/item/13014), [Muffin](/item/13014)) then


muffin = 3;

elseif( **You turn in:** [Muffin](/item/13014), [Muffin](/item/13014)) then


muffin = 2;

elseif( **You turn in:** [Muffin](/item/13014)) then


muffin = 1;



if(muffin > 0) then


repeat



>**Pandos Flintside says:** Mmmm. This smells delicious. Oh great!! No milk!! Don't you have any sense?! Just tell me the name of the bakery and I will run and get it myself. I am sure Lady Shae will be safe.



* __Faction:__ [Faydarks Champions](/faction/246) (1)



* __Faction:__ [King Tearis Thex](/faction/279) (1)



* __Faction:__ [Clerics of Tunare](/faction/226) (1)



* __Faction:__ [Soldiers of Tunare](/faction/310) (1)



* __Faction:__ [Crushbone Orcs](/faction/234) (-1)



 **You receive:** 0 (+5 exp)



muffin = muffin - 1;


until muffin == 0

**This NPC *should* return incorrect items given.**

## Timer(s)

local xloc = e.self:GetX();

local yloc = e.self:GetY();


if(xloc == -693 and yloc == -[King Tearis Thex](/faction/279) and Bakery == 1) then


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


