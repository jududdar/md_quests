# abandoned heretic pet
## Arrive at Waypoint Script

if(e.wp == 5) then


if(**spawned NPC:**  [\#a skeleton](/npc/38009) or **spawned NPC:**  [\#\#a skeleton](/npc/38010)) then



>**abandoned heretic pet says:** Speed up the digging my pets!



if(**spawned NPC:**  [\#a skeleton](/npc/38009)) then




eq.get_entity_list():GetMobByNpcTypeID( [\#a skeleton](/npc/38009)):Say("We are not your pets!");





if(**spawned NPC:**  [\#\#a skeleton](/npc/38010)) then




eq.get_entity_list():GetMobByNpcTypeID( [\#\#a skeleton](/npc/38010)):Say("We will speed up when you return our mining caps. There are falling rocks all over this place! We could get killed!");




elseif(e.wp == 7) then


>**abandoned heretic pet says:** Blast you, skeletons!  Why I ever resurrected you, I don't know!
end
