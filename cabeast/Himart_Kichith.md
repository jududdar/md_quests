# Himart Kichith

[Himart Kichith](/npc/106017) is a level 50 Iksar Warrior that spawns in [Cabilis East](/zone/106).

Their primary faction is [Legion of Cabilis](/faction/441).



## Dialog

**You say:** `hail`


>**Himart Kichith says:** Greetings young one, I am Himart Kichith, shaman of the Scaled Mystics and storekeeper of valuable knowledge of the past. I am always looking for knowledge of the past in the form of spells and [rare scrolls]. If you are interested in a tidy profit perhaps you would be willing to help me.

**You say:** `rare scroll`


>**Himart Kichith says:** The remaining scrolls are very rare indeed. Very few have surfaced over the past few years. Should you happen to find more than you can use, return one of them to me and I shall grant you even more power. I still seek the Talisman of Jasinth, Spirit of Scale, Cripple, and the third rank of Cannibalize.











## Turn-Ins



local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19269" data-url="19269" class="tooltip-link link">Spell: Cripple</a>, 19238, 19264, 19272 x 1

if(count > 0) then

repeat

>**Himart Kichith says:** We have both gained much knowledge today.

 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19267" data-url="19267" class="tooltip-link link">Spell: Talisman of Shadoo</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19271" data-url="19271" class="tooltip-link link">Spell: Shroud of the Spirits</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19274" data-url="19274" class="tooltip-link link">Spell: Torrent of Poison</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19266" data-url="19266" class="tooltip-link link">Spell: Insidious Decay</a>) (+1000 exp)

 

count = count - 1;

until count == 0;



**This NPC *should* return incorrect items given.**


