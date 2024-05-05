# Dragoon T\`Vex



[Dragoon T\`Vex](/npc/93084) is a level 50 Dark Elf Warrior that spawns in [The Overthere](/zone/93).



## Signals

if(e.signal==1) then


eq.stop();


e.self:MoveTo(2723,2366,-49,198,true);

elseif(e.signal==2) then


e.self:MoveTo(2734,2476,-49,195,true);

elseif(e.signal==3) then


e.self:SetRunning(true);


eq.start(10);
end



## Arrive at Waypoint Script

if(e.wp==28) then


e.self:SetRunning(false);
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





