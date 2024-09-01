# a mind burrower

[a mind burrower](/npc/173003) is a level 52 Worm Warrior that spawns in [The Maiden's Eye](/zone/173).

Their primary faction is [KoS-ME](/faction/5063).

## On NPC Spawn

**Set a timer** named *depop* for 140 seconds







## Combat

if a mind burrower enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");









## Timer(s)

if(e.timer == "depop") then

**a mind burrower despawns.**



