# Kromrif Death Squad



[Kromrif Death Squad](/npc/116014) is a level 43 Giant Warrior that spawns in [Eastern Wastes](/zone/116).



## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


**Kromrif Death Squad despawns.**
end



## On NPC Death

**Stop timer** named *depop*