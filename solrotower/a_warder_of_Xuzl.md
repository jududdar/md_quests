# a warder of Xuzl

[a warder of Xuzl](/npc/212415) is a level 1 Fire Elemental Warrior that spawns in [Tower of Solusek Ro](/zone/212).

Their primary faction is [KOS](/faction/5017).

## On NPC Spawn
**Set a timer** named *depop* for 3600 seconds




## Timer(s)
if ( e.timer == "depop" ) then
**a warder of Xuzl despawns.**





## Combat
if  a warder of Xuzl enters combat  then
eq.pause_timer("depop");
else
eq.resume_timer("depop");

