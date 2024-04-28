# Undogo Digolo
## Combat


if  Undogo Digolo enters combat  then


HelpMe(e);


**Set a timer** named *help* for 300 seconds

else


**Stop timer** named *help*
end

## Timer(s)


if ( e.timer == "help" ) then


**Undogo Digolo shouts:** <span class="text-danger">Undogo, oldogo, gaba, daga!</span>


HelpMe(e);
end

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



end
