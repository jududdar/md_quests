# a swarming fly



[a swarming fly](/npc/200254) is a level 58 Fly Warrior that spawns in [The Crypt of Decay](/zone/200).



## On NPC Spawn

**Set a timer** named *depop* for 900 seconds


## Timer(s)

**a swarming fly despawns.**


## Combat

if  a swarming fly enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
