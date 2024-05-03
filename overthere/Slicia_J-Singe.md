# Slicia J-Singe


## Dialog

**You say:** `Hail`



>**Slicia J-Singe says:** Why is it that you have come to this place? If you are coming here to search for [magical scrolls], just get back on that so-called ship you came here on and forget everything you thought you heard.

**You say:** `magical scrolls`



>**Slicia J-Singe says:** Is your hearing failing you!? Unless you [have something I need]. be gone!

**You say:** `i have something you need`



>**Slicia J-Singe says:** I must have the scrolls of Gift of Xev. Bristlebane's Bundle. Quiver of Marr. and the Scars of Sigil. If you don't have one of these. leave my sight!  If you do. I think we can work up a fair trade.
end



## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19351" data-url="19351" class="tooltip-link link">Spell: Bristlebane\`s Bundle</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19347" data-url="19347" class="tooltip-link link">Spell: Gift of Xev</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19354" data-url="19354" class="tooltip-link link">Spell: Quiver of Marr</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19358" data-url="19358" class="tooltip-link link">Spell: Scars of Sigil</a>}

if(count > 0) then


repeat



>**Slicia J-Singe says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19368" data-url="19368" class="tooltip-link link">Spell: Boon of Immolation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19346" data-url="19346" class="tooltip-link link">Spell: Scintillation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19355" data-url="19355" class="tooltip-link link">Spell: Vocarate: Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19357" data-url="19357" class="tooltip-link link">Spell: Vocarate: Air</a>) (+1000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





