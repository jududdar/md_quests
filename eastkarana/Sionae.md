# Sionae
## On NPC Spawn

**Set a timer** named *despawn* for 3600 seconds
## Timer(s)

**Stop timer** named *despawn*

**Sionae despawns.**
## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1053.png" alt="" /> <a
                                href="/item/20450" data-url="20450" class="tooltip-link link">Braided Grass Amulet</a>) then


>**Sionae says:** I see that the time has come. Take the amulet and give it to the third of our kin, Nuien. I will meet you at the gathering.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1053.png" alt="" /> <a
                                href="/item/20451" data-url="20451" class="tooltip-link link">Frayed Braided Grass Amulet</a> 

 


**Spawn NPC:**  [Nuien](/npc/15167) at (**y:** -3657, **x:** 300)


eq.move_to(-1595,-3670,-18,0,true);

**This NPC *should* return incorrect items given.**

## Signals

if(e.signal == 1) then


>*Sionae shivers as her power flows into the air above the gathering.*


**Sionae casts:** [Call of the Storm](/spell/790) on themselves.
end
