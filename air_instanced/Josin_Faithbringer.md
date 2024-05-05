# Josin Faithbringer



[Josin Faithbringer](/npc/71052) is a level 55 Efreeti Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).



## Dialog

**You say:** `Hail`



>**Josin Faithbringer says:** Greetings, Soandso.  Are you ready to begin your test of faith?

**You say:** `test of faith`



>**Josin Faithbringer says:** I have faith that you will do well. Choose Alan or Deric

**You say:** `Alan`



>**Josin Faithbringer says:** Take and read this book. When you are done, hand it back to me and I will summon him.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18540" data-url="18540" class="tooltip-link link">Practical Arts</a>

**You say:** `Deric`



>**Josin Faithbringer says:** Take and read this book. When you are done, hand it back to me and I will summon him.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18541" data-url="18541" class="tooltip-link link">True Healing</a>
end




## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18540" data-url="18540" class="tooltip-link link">Practical Arts</a>) then 


>**Josin Faithbringer says:** Farewell.


**Spawn NPC:**  [Alan Harten](/npc/71080) at (**y:** 1361.6, **x:** 660.7)


**Josin Faithbringer despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18541" data-url="18541" class="tooltip-link link">True Healing</a>) then 


>**Josin Faithbringer says:** Farewell.


**Spawn NPC:**  [Deric Lennox](/npc/71083) at (**y:** 1338.0, **x:** 660.7)


**Josin Faithbringer despawns.**

**This NPC *should* return incorrect items given.**

end