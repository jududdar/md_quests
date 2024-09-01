# Lord Vyemm

[Lord Vyemm](/npc/124003) is a level 66 Dragon Warrior that spawns in [Temple of Veeshan](/zone/124).

Their primary faction is [Guardians of Veeshan](/faction/467).







## On NPC Spawn

**Spawn NPC:**  [a guardian spirit](/npc/124157) at (**y:** 461, **x:** -679)





function event_death(e)



local npc_list = eq.get_entity_list():GetNPCList();



if ( npc_list ) then

for npc in npc_list.entries do

if ( npc:GetNPCTypeID() == 124157 and npc:GetX() == -679 and npc:GetY() == 461 ) then

npc:Depop();

break;













## Combat



if  Lord Vyemm enters combat  then

**Set a timer** named *help* for 300 seconds

HelpMe(e);

else

**Stop timer** named *help*









## Timer(s)

if(e.timer == "help") then

HelpMe(e);







function HelpMe(e)

local aaryonar = eq.get_entity_list():GetMobByNpcTypeID(124010);



if (aaryonar.valid) then

aaryonar:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);



