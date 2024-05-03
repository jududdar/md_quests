# Solusek Ro


## Combat

if  Solusek Ro enters combat  then


**Set a timer** named *anti_cheat* for 30 seconds

else


**Stop timer** named *anti_cheat*
end



## Timer(s)


if ( e.timer == "anti_cheat" ) then



if ( e.self:GetZ() < 240 and e.self:GetHPRatio() < 50 ) then






local npcList = eq.get_entity_list():GetNPCList();



for npc in npcList.entries do








if ( npc.valid and npc:GetNPCTypeID() == 212041 and not npc:IsEngaged() ) then 





npc:GMMove(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0);








e.self:HealDamage(100000);

end



## On NPC Death

**Spawn NPC:**  [A Planar Projection](/npc/212420) at (**y:** -815, **x:** 0)

**Signaled to:**  [A Planar Projection](/npc/212420)