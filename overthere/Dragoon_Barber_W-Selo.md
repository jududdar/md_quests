# Dragoon Barber W\`Selo



[Dragoon Barber W\`Selo](/npc/93124) is a level 50 Dark Elf Cleric that spawns in [The Overthere](/zone/93).



## Signals

if(e.signal==1) then


eq.stop();


e.self:MoveTo(2864,2997,-49,35,true);

elseif(e.signal==2) then


e.self:MoveTo(2733,2490,-49,195,true);

elseif(e.signal==3) then


e.self:SetRunning(true);


eq.start(13);
end



## Arrive at Waypoint Script

if(e.wp==28) then


e.self:SetRunning(false);
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





