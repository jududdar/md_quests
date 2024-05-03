# Legionnaire Claudius


## Dialog

local vahn = eq.get_entity_list():GetMobByNpcTypeID( [Vahn](/npc/160137));

**You say:** `traitor to the Validus Custodus`



if(vahn.valid) then



**Spawn NPC:**  [\#Vahn](/npc/160140) at (**y:** , **x:** )



**Despawn NPC:**  [Vahn](/npc/160137)



**Spawn NPC:**  [\#\#Legionnaire Claudius](/npc/160141) at this location.



**Legionnaire Claudius despawns.**

end



## Arrive at Waypoint Script

local vahn = eq.get_entity_list():GetMobByNpcTypeID( [Vahn](/npc/160137));

if(e.wp == 34) then


**Spawn NPC:**  [Vahn](/npc/160137) at (**y:** 67, **x:** -1149)

elseif(e.wp == 35) then


if(vahn.valid) then



vahn:Emote("speaks with Legionnaire Claudius in hushed tones. Their whispers cannot be heard, but there is certainly something suspicious in their demeanor.");


elseif(e.wp == 36) then


if(vahn.valid) then



vahn:Emote("passes something to Claudius and gets a rolled up parchment in return. Their business appears to be completed and both parties prepare to go about their business.");


elseif(e.wp == 37) then


if(vahn.valid) then



vahn:Emote("glances in either direction and nods at Claudius before disappearing back into the shadows.");



>*Legionnaire Claudius looks to Vahn tentatively, 'We shall meet again soon.'*



vahn:Say("Perhaps");



vahn:Emote("steps out of the shadows as though appearing out of thin air.");



**Despawn NPC:**  [Vahn](/npc/160137)


**Legionnaire Claudius despawns.**
end