# Leistr



[Leistr](/npc/209056) is a level 65 Stormrider Rogue that spawns in [Bastion of Thunder](/zone/209).



## Combat

if  Leistr enters combat  then


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
