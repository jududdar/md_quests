# Stonehand



[Stonehand](/npc/171009) is a level 50 Stonegrabber Warrior that spawns in [The Grey](/zone/171).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Timer(s)

if(e.timer == "depop") then


**Stonehand despawns.**
end



## Combat

if Stonehand enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
