# a blood starved wolf



[a blood starved wolf](/npc/174116) is a level 32 Wolf Warrior that spawns in [The Dawnshroud Peaks](/zone/174).



## On NPC Spawn

**Set a timer** named *depop* for 95 seconds


## Timer(s)

**a blood starved wolf despawns.**


## Combat

if a blood starved wolf enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end