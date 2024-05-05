# Hollish Tnoops



[Hollish Tnoops](/npc/9144) is a level 14 Dark Elf Warrior that spawns in [West Freeport](/zone/9).



## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds

e.self:SetRunning(true);


## Combat

if Hollish Tnoops enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

**Hollish Tnoops despawns.**
end