# a reanimated corpse

[a reanimated corpse](/npc/160096) is a level 33 Zombie Warrior that spawns in [Katta Castellum](/zone/160).

Their primary faction is [KOS](/faction/5017).

## On NPC Spawn

**Set a timer** named *depop* for 120 seconds







## Timer(s)

if(e.timer == "depop") then

**a reanimated corpse despawns.**









## Combat

if a reanimated corpse enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");



