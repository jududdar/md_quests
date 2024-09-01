# A Phoenix Gustlet

[A Phoenix Gustlet](/npc/215412) is a level 50 Phoenix Warrior that spawns in [Plane of Air](/zone/215).

Their primary faction is [KOS](/faction/5017).

## On NPC Spawn

**Set a timer** named *depop* for 600 seconds







## Combat

if  A Phoenix Gustlet enters combat  then

eq.pause_timer("depop");

else

eq.resume_timer("depop");









## Timer(s)

if ( e.timer == "depop" and not e.self:Charmed() ) then

**A Phoenix Gustlet despawns.**



