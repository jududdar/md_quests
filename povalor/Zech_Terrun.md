# Zech Terrun



[Zech Terrun](/npc/208067) is a level 66 Human Warrior that spawns in [Plane of Valor](/zone/208).



## Dialog


local qglobals = eq.get_qglobals(e.other);


**You say:** `hail`



if ( qglobals.aerindar ) then



>*Zech Terrun looks at you humbly. 'I heard about your run in with Aerin\`Dar. The Battalion of Marr salutes you.*


else



>*Zech Terrun stands at attention.*

end
