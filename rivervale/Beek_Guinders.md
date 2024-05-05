# Beek Guinders



[Beek Guinders](/npc/19112) is a level 61 Halfling GM Cleric that spawns in [Rivervale](/zone/19).



## Dialog

**You say:** `hail`



>*Beek Guinders waves enthusiastically and says, Hay, ho, there, young " .. e.other:Race() .. "!  I'd love to yak it up with you but I'm a bit busy at the moment, trying to find some [help].*

**You say:** `help`



>**Beek Guinders says:** Well, we're experimenting with some tanning methods but we're running low on supplies. We need to find someone to go out and [gather some things]. Seems no one wants to do an honest day's work any more. I'd do it myself but, errrr, my, uhhh, foot hair has been hurting lately... yes, that's it.

**You say:** `heal`



>**Beek Guinders says:** Hey! That is not my responsibility! Go speak with Hendi Mrubble. She is the one who got stuck with that duty.

**You say:** `gather some thing`



>**Beek Guinders says:** Ahhh, excellent! Okay, first, we'll need a couple of wolf pelts. They don't have to be perfect, completely ruined would work just fine, hehe. I'll also need a black wolf skin and a handful of berries. The berries you should be able to find out in the Thicket. I hear they grow in a small canyon near the lone tower. Hurry, hurry!
end



## Turn-Ins



local text = "Whoooops! I'll need the two ruined wolf pelts along with the berries and black wolf skin before I can reward you, Soandso. Don't dawdle now.";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18731" data-url="18731" class="tooltip-link link">A tattered note</a>) then 


>**Beek Guinders says:** Aye. Welcome. my fur-footed friend. My name is Beek Guinders. and I am guildmaster here at the Chapel of Mischief. Here is our guild tunic. Wear it with pride, as it will set you apart from the crowd.


Your faction standing with [Priests of Mischief](/faction/300) got better (<span class='text-success'>+100</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+15</span>)


Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+15</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13538" data-url="13538" class="tooltip-link link">Faded Gold Felt Tunic*</a> (+20 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1037.png" alt="" /> <a
                                href="/item/13045" data-url="13045" class="tooltip-link link">Berries</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13782" data-url="13782" class="tooltip-link link">Ruined Wolf Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_553.png" alt="" /> <a
                                href="/item/13782" data-url="13782" class="tooltip-link link">Ruined Wolf Pelt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_556.png" alt="" /> <a
                                href="/item/13758" data-url="13758" class="tooltip-link link">Black Wolf Skin</a>) then 


>**Beek Guinders says:** Hey, great! You found the materials! We'll get to work right away. If you find any more, please come by again. Here's a little something for your troubles, friend.





Your faction standing with [Priests of Mischief](/faction/300) got better (<span class='text-success'>+3</span>)


Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15014" data-url="15014" class="tooltip-link link">Spell: Strike</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15201" data-url="15201" class="tooltip-link link">Spell: Flash of Light</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15207" data-url="15207" class="tooltip-link link">Spell: Divine Aura</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15208" data-url="15208" class="tooltip-link link">Spell: Lull</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/16303" data-url="16303" class="tooltip-link link">Spell: Gate</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


