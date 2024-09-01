# A comet

[A comet](/npc/209123) is a level 60 Dervish Warrior that spawns in [Bastion of Thunder](/zone/209).

Their primary faction is [Greater Jord Giants](/faction/1610).

## On NPC Spawn
**Set a timer** named *depop* for 600 seconds




## Timer(s)
if ( e.timer == "depop" ) then
**A comet despawns.**





## Combat
if  A comet enters combat  then
eq.pause_timer("depop");
else
eq.resume_timer("depop");

