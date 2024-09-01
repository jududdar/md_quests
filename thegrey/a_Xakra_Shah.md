# a Xakra Shah

[a Xakra Shah](/npc/171003) is a level 44 Worm Warrior that spawns in [The Grey](/zone/171).

Their primary faction is [KOS](/faction/5017).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds







## Timer(s)

if(e.timer == "depop") then

**a Xakra Shah despawns.**









## Combat

if a Xakra Shah enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");



