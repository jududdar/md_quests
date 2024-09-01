# The Dreamkeeper

[The Dreamkeeper](/npc/204480) is a level 64 Banshee Shadow Knight that spawns in [Plane of Nightmares](/zone/204).

Their primary faction is [KOS Plane of Nightmare](/faction/5029).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds







## Combat

if  The Dreamkeeper enters combat  then

eq.pause_timer("depop");

else

eq.resume_timer("depop");









## Timer(s)

if ( e.timer == "depop" ) then

**The Dreamkeeper despawns.**



