# rabid snow cougar



[rabid snow cougar](/npc/110012) is a level 35 Puma Warrior that spawns in [Iceclad Ocean](/zone/110).



## On NPC Spawn

**Set a timer** named *attack* for 1 seconds

**Set a timer** named *depop* for 120 seconds


## Timer(s)

if(e.timer == "attack") then


**rabid snow cougar attacks NPC:**  [a lost pirate](/npc/110057)


**Stop timer** named *attack*

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**rabid snow cougar despawns.**
end