# Karg IceBear
## On NPC Spawn

 **Set a timer** named *depop* for 3600 seconds
## Timer(s)

**Karg IceBear despawns.**
## Dialog

**You say:** `hail`



>**Karg IceBear says:** Hail, traveller! I am Karg of Clan Icebear, lone hunter of the Everfrost Peaks. Have you seen any polar bears about?

**You say:** `yes`



>**Karg IceBear says:** I hunt polar bears and furnish cloaks from their [pelts]. They keep you warm in this cold weather.

**You say:** `pelt`



>**Karg IceBear says:** Have you some polar bear pelts? You know I can furnish warm cloaks from them, and for you I will do it for the measly sum of 5 platinum pieces.

**You say:** `werewolf`



>**Karg IceBear says:** Werewolf?! I have not seen a werewolf in years. Have you slain one and collected its [skin] or [claws]?

**You say:** `skin`



>**Karg IceBear says:** You have managed to procure a werewolf skin?? Amazing! Well then, I will let you know that for a fee of 100 platinum, I can craft a hearty cloak for you if you leave the skin and the coin with me.
 
**You say:** `claw`



>**Karg IceBear says:** Oh, a werewolf claw? If you were to give me the claw and 75 platinum, I could craft excellent gauntlets.
end

## Turn-Ins



local text = "OK! Now, where is the rest?";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_835.png" alt="" /> <a
                                href="/item/13761" data-url="13761" class="tooltip-link link">Polar Bear Skin</a>,platinum = 5) then 


>**Karg IceBear says:** Here is your polar bear cloak! It will serve you well and keep you warm even in the coldest conditions. Farewell, friend



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_839.png" alt="" /> <a
                                href="/item/2912" data-url="2912" class="tooltip-link link">Polar Bear Cloak</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_556.png" alt="" /> <a
                                href="/item/13714" data-url="13714" class="tooltip-link link">Werewolf Pelt</a>,platinum = 100) then 


>**Karg IceBear says:** It has been a long time since I crafted items from werewolves. I hope this aids you in your journeys. Farewell, friend, until we meet again.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_842.png" alt="" /> <a
                                href="/item/2401" data-url="2401" class="tooltip-link link">Werewolf Skin Cloak</a> 

 




elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_743.png" alt="" /> <a
                                href="/item/13715" data-url="13715" class="tooltip-link link">Werewolf Claws</a>,platinum = 75) then 


>**Karg IceBear says:** It has been a long time since I crafted items from werewolves. I hope this aids you in your journeys. Farewell, friend, until we meet again.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_518.png" alt="" /> <a
                                href="/item/2402" data-url="2402" class="tooltip-link link">Lupine Claw Gauntlets</a> 

 




**This NPC *should* return incorrect items given.**
;
