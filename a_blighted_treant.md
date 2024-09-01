# a blighted treant

[a blighted treant](/npc/204459) is a level 55 Treant Warrior that spawns in [Plane of Nightmares](/zone/204).

Their primary faction is [KOS Plane of Nightmare](/faction/5029).

## On NPC Spawn

**Set a timer** named *depop* for 100 seconds







## Combat

if  a blighted treant enters combat  then

eq.pause_timer("depop");

else

eq.resume_timer("depop");









## Timer(s)

if ( e.timer == "depop" ) then

**a blighted treant despawns.**



