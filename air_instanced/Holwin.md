# Holwin



[Holwin](/npc/71046) is a level 55 Efreeti Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).



## Dialog

**You say:** `Hail`



>**Holwin says:** Peace to you, Soandso.  I see that you have come far along the path of tranquility and enlightenment.  Do you wish to test yourself further, and perhaps complete the path you started on so long ago?

**You say:** `test`



>**Holwin says:** Then, choose. Do you wish to be tested by Ton Po or Wu?

**You say:** `wu`



>**Holwin says:** Take this and read it.  Once you are finished, I will summon the Tranquil's most enlightened follower.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18539" data-url="18539" class="tooltip-link link">Strength</a>

**You say:** `ton po`



>**Holwin says:** Take this book and read about the legendary Ton Po.  When you are finished, hand it back, and I will summon the master for you.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18538" data-url="18538" class="tooltip-link link">Tranquility</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18539" data-url="18539" class="tooltip-link link">Strength</a>) then 


>**Holwin says:** Farewell.


**Spawn NPC:**  [Wu the Enlightened](/npc/71097) at (**y:** 1332.3, **x:** 660.0)


**Holwin despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18538" data-url="18538" class="tooltip-link link">Tranquility</a>) then 


>**Holwin says:** Farewell.


**Spawn NPC:**  [Ton Po](/npc/71096) at (**y:** 1315.0, **x:** 660.0)


**Holwin despawns.**

**This NPC *should* return incorrect items given.**

end