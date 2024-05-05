# Hrani



[Hrani](/npc/209058) is a level 65 Stormrider Monk that spawns in [Bastion of Thunder](/zone/209).



## Combat

if  Hrani enters combat  then


**Set a timer** named *tick* for 6 seconds

else


**Stop timer** named *tick*
end



## Timer(s)

if ( e.timer == "tick" ) then


local npc = **spawned NPC:**  [Kuanbyr Hailstorm](/npc/209061); 


if ( npc and npc.valid and e.self:GetTarget() and e.self:GetTarget().valid ) then



npc:AddToHateList(e.self:GetTarget(), 1);

end
