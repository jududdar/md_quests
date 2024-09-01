# Salczek the Fleshgrinder

[Salczek the Fleshgrinder](/npc/207027) is a level 69 Tormentor Warrior that spawns in [Torment, the Plane of Pain](/zone/207).

Their primary faction is [Servants of Saryrn](/faction/1624).

## On NPC Spawn
eq.set_next_hp_event(50);


function event_hp(e)
e.self:ModifyNPCStat("special_abilities", "4,1,20"); 
