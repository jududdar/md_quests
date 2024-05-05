# Wizard Schrock



[Wizard Schrock](/npc/71047) is a level 55 Efreeti Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).



## Dialog

**You say:** `hail`



>**Wizard Schrock says:** Greetings, Soandso. Do you believe that you are a [great Wizard]?

**You say:** `great wizard`



>**Wizard Schrock says:** I will not take your word for it! You must prove your greatness to my apprentices. Do you wish to be tested by Neasin or by Abec?

**You say:** `Neasin`



>**Wizard Schrock says:** Neasin it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the mighty wizard Neasin to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18530" data-url="18530" class="tooltip-link link">Fire and Ice</a>

**You say:** `Abec`



>**Wizard Schrock says:** Abec it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the mighty wizard Abec to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18531" data-url="18531" class="tooltip-link link">Knowledge and Power</a>
end




## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18530" data-url="18530" class="tooltip-link link">Fire and Ice</a>) then 


>**Wizard Schrock says:** Till next time!  Farewell!


**Spawn NPC:**  [Neasin Leornic](/npc/71092) at (**y:** 1304.3, **x:** 585)


**Wizard Schrock despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18531" data-url="18531" class="tooltip-link link">Knowledge and Power</a>) then 


>**Wizard Schrock says:** Till next time!  Farewell!


**Spawn NPC:**  [Abec Ianor](/npc/71079) at (**y:** 1304.3, **x:** 585)


**Wizard Schrock despawns.**

**This NPC *should* return incorrect items given.**

end