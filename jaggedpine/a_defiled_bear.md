# a defiled bear

[a defiled bear](/npc/181015) is a level 40 Bear Warrior that spawns in [Jaggedpine Forest](/zone/181).

Their primary faction is [KOS](/faction/5017).



## On NPC Spawn

**Set a timer** named *depop* for 300 seconds







## Timer(s)

if(e.timer == "depop") then

**a defiled bear despawns.**









## Combat

if a defiled bear enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");



