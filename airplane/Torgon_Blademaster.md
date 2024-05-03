# Torgon Blademaster


## Dialog

**You say:** `hail`



>**Torgon Blademaster says:** Greetings, Soandso. Are you a [true warrior]?

**You say:** `true warrior`



>**Torgon Blademaster says:** Then you shall be tested as one. Choose. Do you wish to be tested by Falorn or Ogog?

**You say:** `falorn`



>**Torgon Blademaster says:** So be it, warrior.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the mighty warrior Falorn to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18520" data-url="18520" class="tooltip-link link">Falorn story</a>

**You say:** `ogog`



>**Torgon Blademaster says:** Ogog?  You are indeed brave for choosing that brute.  Take this book telling the tale of Ogog and read it.  When you are finished, hand it back to me.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18521" data-url="18521" class="tooltip-link link">Ogog Story</a>
end




## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18520" data-url="18520" class="tooltip-link link">Falorn story</a>) then 



>**Torgon Blademaster says:** Falorn, come forth!


**Spawn NPC:**  [Falorn](/npc/71067) at (**y:** 1392.4, **x:** 563.3)


**Torgon Blademaster despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18521" data-url="18521" class="tooltip-link link">Ogog Story</a>) then 


>**Torgon Blademaster says:** Farewell.


**Spawn NPC:**  [Ogog](/npc/71064) at (**y:** 1392.4, **x:** 563.3)


**Torgon Blademaster despawns.**

**This NPC *should* return incorrect items given.**


