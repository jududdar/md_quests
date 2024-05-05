# Draz Nurakks Image



[Draz Nurakks Image](/npc/96010) is a level 53 Iksar Beastlord that spawns in [Timorous Deep](/zone/96).



## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds


## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


**Draz Nurakks Image despawns.**
end



## Combat

if Draz Nurakks Image enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
