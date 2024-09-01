# Undogo Digolo

[Undogo Digolo](/npc/127015) is a level 65 Totem Ranger that spawns in [Plane of Growth](/zone/127).

Their primary faction is [Servants of Tunare](/faction/438).



## Combat



if  Undogo Digolo enters combat  then

HelpMe(e);

**Set a timer** named *help* for 300 seconds

else

**Stop timer** named *help*









## Timer(s)



if ( e.timer == "help" ) then

**Undogo Digolo shouts:** <span class="text-danger">Undogo, oldogo, gaba, daga!</span>

HelpMe(e);







function HelpMe(e)



local helpers = {

[127027] = 1,	

[127103] = 1,	

[127026] = 1,	

};



local list = eq.get_entity_list():GetNPCList();



if ( list ) then



for npc in list.entries do



if ( helpers[npc:GetNPCTypeID()] and npc.valid ) then

npc:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);







