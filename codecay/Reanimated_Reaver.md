# Reanimated Reaver



[Reanimated Reaver](/npc/200259) is a level 60 Skeleton Warrior that spawns in [The Crypt of Decay](/zone/200).



## On NPC Spawn

**Set a timer** named *depop* for 1500 seconds


## Timer(s)

**Reanimated Reaver despawns.**


## Combat

if  Reanimated Reaver enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
