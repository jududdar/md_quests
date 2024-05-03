# Magus Frinon


## Dialog

**You say:** `Hail`



>**Magus Frinon says:** Greetings, Soandso.  Have you come here to test your abilities as a magician?

**You say:** `test`



>**Magus Frinon says:** I am glad to hear that. Please choose from one of my instructors. Frederic or Roanis.

**You say:** `Frederic`



>**Magus Frinon says:** Frederic it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the magician Frederic to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18532" data-url="18532" class="tooltip-link link">Forms of Magic</a>

**You say:** `Roanis`



>**Magus Frinon says:** Roanis it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the magician Roanis to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18533" data-url="18533" class="tooltip-link link">Channeling</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18532" data-url="18532" class="tooltip-link link">Forms of Magic</a>) then 


>**Magus Frinon says:** Till next time!  Farewell!


**Spawn NPC:**  [Frederic Calermin](/npc/71088) at (**y:** 1304.1, **x:** 614.5)


**Magus Frinon despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18533" data-url="18533" class="tooltip-link link">Channeling</a>) then 


>**Magus Frinon says:** Till next time!  Farewell!


**Spawn NPC:**  [Roanis Elindar](/npc/71094) at (**y:** 1304.1, **x:** 614.5)


**Magus Frinon despawns.**

**This NPC *should* return incorrect items given.**

end