# Valdanov Zevfeer



[Valdanov Zevfeer](/npc/172014) is a level 62 Vampire Necromancer that spawns in [The Tenebrous Mountains](/zone/172).



## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds


## Timer(s)

if(e.timer == "depop") then


**Valdanov Zevfeer despawns.**
end



## Combat

if Valdanov Zevfeer enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
