# Derena Leflor



[Derena Leflor](/npc/75039) is a level 11 Erudite Warrior that spawns in [Paineel](/zone/75).



## Arrive at Waypoint Script

if(e.wp == 14) then


eq.set_anim(75039,1);

elseif(e.wp == 28) then


e.self:DoAnim(36);

elseif(e.wp == 52) then


eq.set_anim(75039,1);
end




