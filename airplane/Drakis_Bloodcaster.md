# Drakis Bloodcaster



[Drakis Bloodcaster](/npc/71053) is a level 55 Efreeti Warrior that spawns in [Plane of Sky](/zone/71).




## Dialog

**You say:** `hail`



>**Drakis Bloodcaster says:** Greetings, " .. e.other:Race() .. ". Are you ready to begin?

**You say:** `ready`



>**Drakis Bloodcaster says:** Then choose, necromancer. Do you wish to be tested by Dugaas or Jzil?

**You say:** `jzil`



>**Drakis Bloodcaster says:** Take this tome and read it.  When you are finished, return it to me and I will summon Jzil.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18536" data-url="18536" class="tooltip-link link">Shadowy Thoughts</a>

**You say:** `Dugaas`



>**Drakis Bloodcaster says:** Take this book and read it then.  When you are finished, hand it back to me and I will summon the vile Dugaas.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18537" data-url="18537" class="tooltip-link link">Pomp and Circumstance</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18536" data-url="18536" class="tooltip-link link">Shadowy Thoughts</a>) then 


>**Drakis Bloodcaster says:** Farewell.


**Spawn NPC:**  [Jzil GSix](/npc/71074) at (**y:** 1305, **x:** 654.9)


**Drakis Bloodcaster despawns.**

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18537" data-url="18537" class="tooltip-link link">Pomp and Circumstance</a>) then 


>**Drakis Bloodcaster says:** Farewell.


**Spawn NPC:**  [Dugaas Helpyre](/npc/71084) at (**y:** 1305, **x:** 661.6)


**Drakis Bloodcaster despawns.**

**This NPC *should* return incorrect items given.**

end