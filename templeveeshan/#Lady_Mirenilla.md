# Lady Mirenilla



[Lady Mirenilla](/npc/124077) is a level 66 Dragon Shadow Knight that spawns in [Temple of Veeshan](/zone/124).





## On NPC Spawn

**Spawn NPC:**  [a guardian spirit](/npc/124157) at (**y:** 562, **x:** -686)
function event_death(e)


local npc_list = eq.get_entity_list():GetNPCList();



if ( npc_list ) then


for npc in npc_list.entries do



if ( npc:GetNPCTypeID() ==  [a guardian spirit](/npc/124157) and npc:GetX() == -686 and npc:GetY() == 562 ) then




npc:Depop();




break;



end



## Combat


if  Lady Mirenilla enters combat  then


**Set a timer** named *help* for 300 seconds


HelpMe(e);

else


**Stop timer** named *help*
end



## Timer(s)

if(e.timer == "help") then


HelpMe(e);
end

function HelpMe(e)

local aaryonar = eq.get_entity_list():GetMobByNpcTypeID(124010);



if (aaryonar.valid) then


aaryonar:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);
end
