# Ranger Spirit



[Ranger Spirit](/npc/71054) is a level 55 Efreeti Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).



## Dialog

**You say:** `Hail`



>**Ranger Spirit says:** Greetings, Soandso. Are you a true servant of the Pine?

**You say:** `servant of the pine`



>**Ranger Spirit says:** Very well my friend. In order to reach your true potential you must pass many tests. Relinin Skyrunner and Gordon Treecaller are here to perform these tests. Please choose one.

**You say:** `relinin`



>**Ranger Spirit says:** Relinin Skyrunner, you say. True to Tunare is she.  Take this book and read it. When you feel you know it well, return it and Relinin will appear to test you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18546" data-url="18546" class="tooltip-link link">Sisters and Life</a>

**You say:** `gordon`



>**Ranger Spirit says:** Ahhh, Gordon Treecaller.  Many say he is the finest swordsman ever. Read of his tale and return the book when you are finished.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18547" data-url="18547" class="tooltip-link link">The Mother</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18546" data-url="18546" class="tooltip-link link">Sisters and Life</a>) then 


>**Ranger Spirit says:** Relinin Skyrunner, I summon thee.


**Spawn NPC:**  [Relinin Skyrunner](/npc/71095) at (**y:** 1399.5, **x:** 617.1)


**Ranger Spirit despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18547" data-url="18547" class="tooltip-link link">The Mother</a>) then 


>**Ranger Spirit says:** Gordon Treecaller, I summon thee.


**Spawn NPC:**  [Gordon Treecaller](/npc/71090) at (**y:** 1400.1, **x:** 592.8)


**Ranger Spirit despawns.**

**This NPC *should* return incorrect items given.**

end