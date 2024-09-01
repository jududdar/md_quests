# Kal`Vunar

[Kal`Vunar](/npc/124016) is a level 60 Drake Warrior that spawns in [Temple of Veeshan](/zone/124).

Their primary faction is [Guardians of Veeshan](/faction/467).



## Combat

if  Kal-Vunar enters combat  then
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

