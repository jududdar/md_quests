# Sionae
## On NPC Spawn

**Set a timer** named *despawn* for 3600 seconds
## Timer(s)

**Stop timer** named *despawn*

**Sionae despawns.**
## Turn-Ins





if( **You turn in:** [Braided Grass Amulet](/item/20450)) then


>**Sionae says:** I see that the time has come. Take the amulet and give it to the third of our kin, Nuien. I will meet you at the gathering.


 **You receive:**  [Frayed Braided Grass Amulet](/item/20451) 


**Spawn NPC:**  [Nuien](/npc/15167) at (**y:** -3657, **x:** 300)


eq.move_to(-1595,-3670,-18,0,true);

**This NPC *should* return incorrect items given.**

## Signals

if(e.signal == 1) then


>*Sionae shivers as her power flows into the air above the gathering.*


**Sionae casts:** [Call of the Storm](/spell/790) on themselves.
end
