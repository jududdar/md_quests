# a fungi shroom



[a fungi shroom](/npc/174117) is a level 28 Shrieker Warrior that spawns in [The Dawnshroud Peaks](/zone/174).



## On NPC Spawn

**Set a timer** named *depop* for 95 seconds


## Timer(s)

**a fungi shroom despawns.**


## Combat

if a fungi shroom enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end