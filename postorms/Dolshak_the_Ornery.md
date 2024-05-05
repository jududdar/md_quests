# Dolshak the Ornery



[Dolshak the Ornery](/npc/210468) is a level 65 Giant Warrior that spawns in [Plane of Storms](/zone/210).



## On NPC Spawn

if ( **spawned NPC:**  [Neffiken, Lord of Kelek\`Vor](/npc/210251) ) then 
 

**Dolshak the Ornery despawns.**



## On NPC Spawn

**Set a timer** named *depop1* for 900 seconds

**Set a timer** named *depop2* for 4200 seconds


## Combat

if  Dolshak the Ornery enters combat  then


eq.pause_timer("depop1");

else


eq.resume_timer("depop1");
end



## Timer(s)

**Dolshak the Ornery despawns.**