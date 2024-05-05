# a horror construct



[a horror construct](/npc/48376) is a level 63 Dragon Warrior that spawns in [Lost Temple of CazicThule](/zone/48).



## On NPC Spawn

**Set a timer** named *depop* for 500 seconds


## Timer(s)

**a horror construct despawns.**


## Combat

if  a horror construct enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
