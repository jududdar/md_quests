# Dason Goldblade



[Dason Goldblade](/npc/71037) is a level 55 Efreeti Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).



## Dialog

**You say:** `hail`



>**Dason Goldblade says:** Greetings, Soandso.  Are you pure of heart and soul?

**You say:** `Heart and Soul`



>**Dason Goldblade says:** Then choose. Do you wish your purity to be tested by Gregori or Dirkog?

**You say:** `Gregori`



>**Dason Goldblade says:** Gregori is a true and faithful warrior of Tunare.  Read this book and, when you feel confident, hand it back to me.  I will summon Gregori to test you after you have done so.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18526" data-url="18526" class="tooltip-link link">Virtuous Knight</a>

**You say:** `Dirkog`



>**Dason Goldblade says:** Dirkog is a gruff one, but his faith is what all paladins should strive to equal.  Read this book and return it to me.  After you have done so, I shall summon Dirkog to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18527" data-url="18527" class="tooltip-link link">Walk with Evil</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18526" data-url="18526" class="tooltip-link link">Virtuous Knight</a>) then 


>**Dason Goldblade says:** Farewell.


**Spawn NPC:**  [Gregori Lightbringer](/npc/71089) at (**y:** 1331.1, **x:** 563)


**Dason Goldblade despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18527" data-url="18527" class="tooltip-link link">Walk with Evil</a>) then 


>**Dason Goldblade says:** Farewell.


**Spawn NPC:**  [Dirkog Steelhand](/npc/71077) at (**y:** 1331.1, **x:** 563)


**Dason Goldblade despawns.**

**This NPC *should* return incorrect items given.**

end