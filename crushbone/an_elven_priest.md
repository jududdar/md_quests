# an elven priest


## Dialog

**You say:** `king is dead`



>**an elven priest says:** Dead you say? My goodness! Did you manage to slay the warlord too? If you provide me with proof of his death, I can enchant the mace the dwarf gave you as payment. But, I will require the proof first!
end



## Turn-Ins



local text = "Have you the other item I require?";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_637.png" alt="" /> <a
                                href="/item/2301" data-url="2301" class="tooltip-link link">Bracers of Battle</a>) then


>**an elven priest says:** Erollisi be praised! You slew the orc lord! Well, here is a token of my appreciation! Should you wish to have that mace enchanted, just hand me the mace and my token and I shall uphold myof the bargain!





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/1900" data-url="1900" class="tooltip-link link">Prayer Cloth of Tunare</a> (+6000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6315" data-url="6315" class="tooltip-link link">Dwarven Mace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_668.png" alt="" /> <a
                                href="/item/1900" data-url="1900" class="tooltip-link link">Prayer Cloth of Tunare</a>) then


>**an elven priest says:** As promised, here is your mace. Let it not fall into dark hands as its power is hidden until combat when it will reveal its true nature. Fare thee well!





 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_578.png" alt="" /> <a
                                href="/item/6305" data-url="6305" class="tooltip-link link">Screaming Mace</a> (+6000 exp)

 


**an elven priest despawns.**

**This NPC *should* return incorrect items given.**
;
