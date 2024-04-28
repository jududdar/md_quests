# Nuien
## On NPC Spawn

**Set a timer** named *despawn* for 3600 seconds
## Timer(s)

**Stop timer** named *despawn*

**Nuien despawns.**
## Turn-Ins





if **You turn in:** [Frayed Braided Grass Amulet](/item/20451)


>**Nuien says:** So be it. Do as you have done before and find the next. Teloa is the last.


 **You receive:**  [Frayed Braided Grass Amulet](/item/20451) 


**Spawn NPC:**  [Teloa](/npc/15170) at (**y:** -3840, **x:** -2854)


eq.move_to(-1581,-3682,-18,236,true);

**This NPC *should* return incorrect items given.**

## Signals

if(e.signal == 1) then


>*Nuien growls as his power seeps into the earth.*


**Nuien casts:** [Call of the Storm](/spell/790) on themselves.
end
