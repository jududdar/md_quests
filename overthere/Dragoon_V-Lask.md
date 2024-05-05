# Dragoon V\`Lask



[Dragoon V\`Lask](/npc/93125) is a level 50 Dark Elf Warrior that spawns in [The Overthere](/zone/93).



## Signals

if(e.signal==1) then


eq.stop();


e.self:MoveTo(2710,3141,-49,52,true);

elseif(e.signal==2) then


e.self:MoveTo(2733,2480,-49,195,true);

elseif(e.signal==3) then


e.self:SetRunning(true);


eq.start(11);
end



## Arrive at Waypoint Script

if(e.wp==28) then


e.self:SetRunning(false);
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





