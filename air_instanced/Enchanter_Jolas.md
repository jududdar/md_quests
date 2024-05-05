# Enchanter Jolas



[Enchanter Jolas](/npc/71049) is a level 55 Efreeti Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).



## Dialog

**You say:** `hail`



>**Enchanter Jolas says:** Greetings, Soandso.  Have you come here to test your powers of enchantment?

**You say:** `test`



>**Enchanter Jolas says:** I am most honored to be able to help you. Please choose from one of my instructors. Lelulean or Enderbite.

**You say:** `enderbite`



>**Enchanter Jolas says:** Enderbite it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon Enchantress Enderbite to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18535" data-url="18535" class="tooltip-link link">Practical Uses</a>

**You say:** `lelulean`



>**Enchanter Jolas says:** Lelulean it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon Enchantress Lelulean to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18534" data-url="18534" class="tooltip-link link">Tempt and Suggestion</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18535" data-url="18535" class="tooltip-link link">Practical Uses</a>) then 


>**Enchanter Jolas says:** Till next time!  Farewell!


**Spawn NPC:**  [Enderbite](/npc/71085) at (**y:** 1303.2, **x:** 640)


**Enchanter Jolas despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18534" data-url="18534" class="tooltip-link link">Tempt and Suggestion</a>) then 


>**Enchanter Jolas says:** Till next time!  Farewell!


**Spawn NPC:**  [Lelulean](/npc/71104) at (**y:** 1303.2, **x:** 640)


**Enchanter Jolas despawns.**

**This NPC *should* return incorrect items given.**

end