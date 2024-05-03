# Nuien


## On NPC Spawn

**Set a timer** named *despawn* for 3600 seconds


## Timer(s)

**Stop timer** named *despawn*

**Nuien despawns.**


## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1053.png" alt="" /> <a
                                href="/item/20451" data-url="20451" class="tooltip-link link">Frayed Braided Grass Amulet</a>) then


>**Nuien says:** So be it. Do as you have done before and find the next. Teloa is the last.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1053.png" alt="" /> <a
                                href="/item/20451" data-url="20451" class="tooltip-link link">Frayed Braided Grass Amulet</a> 

 


**Spawn NPC:**  [Teloa](/npc/15170) at (**y:** -3840, **x:** -2854)


eq.move_to(-1581,-3682,-18,236,true);

**This NPC *should* return incorrect items given.**



## Signals

if(e.signal == 1) then


>*Nuien growls as his power seeps into the earth.*


**Nuien casts:** [Call of the Storm](/spell/790) on themselves.
end
