# Clockwork MM

[Clockwork MM](/npc/55392) is a level 1 Clockwork Gnome Warrior that spawns in [Ak'Anon](/zone/55).

Their primary faction is [King Ak`Anon](/faction/333).



## On NPC Spawn

**Set a timer** named *depop* for 70 seconds







## Combat

if Clockwork MM enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");









## Timer(s)

**Clockwork MM despawns.**

