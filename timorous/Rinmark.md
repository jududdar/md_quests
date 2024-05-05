# Rinmark



[Rinmark](/npc/96320) is a level 42 Iksar Warrior that spawns in [Timorous Deep](/zone/96).




## On NPC Spawn

**Set a timer** named *Depop3* for 90 seconds


## Combat

if(e.joined == true) then


>**Rinmark says:** Good, your sense of timing is correct. Now begin! Show me that your training has not been wasted.
end



## Timer(s)

if(e.timer == "Depop3") then


**Stop timer** named *Depop3*


**Rinmark despawns.**
end



## On NPC Death

**Stop timer** named *Depop3*

>**Rinmark says:** Your ability is strong, may you serve Cazic Thule with all your might.


## Turn-Ins



**This NPC *should* return incorrect items given.**
