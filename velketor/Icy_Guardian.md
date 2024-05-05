# Icy Guardian



[Icy Guardian](/npc/112029) is a level 52 Spider Rogue that spawns in [Velketor's Labyrinth](/zone/112).



## On NPC Spawn

**Set a timer** named *loot* for 1 seconds


## Timer(s)

**Stop timer** named *loot*

if(math.random(100) < 36) then


setdrop = math.random(100);


if(setdrop < 15) then



e.self:AddItem(1829,1);



e.self:AddItem(1829,1);


elseif(setdrop < 60) then



e.self:AddItem(1829,1);



e.self:AddItem(1829,1);



e.self:AddItem(1829,1);


else



e.self:AddItem(1829,1);



e.self:AddItem(1829,1);



e.self:AddItem(1829,1);



e.self:AddItem(1829,1);

end