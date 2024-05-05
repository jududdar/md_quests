# Legionnaire Claudius



[Legionnaire Claudius](/npc/160141) is a level 42 Human Warrior that spawns in [Katta Castellum](/zone/160).

local count = 0;



## On NPC Spawn

**Set a timer** named *attack* for 2 seconds


## Timer(s)

if(e.timer == "attack") then


count = count + 1;


if(count == 1) then



**Spawn NPC:**  [Legionnaire](/npc/160139) at (**y:** -6, **x:** -1191)


elseif(count == 2) then



**Spawn NPC:**  [Legionnaire](/npc/160139) at (**y:** -6, **x:** -1191)



**Spawn NPC:**  [Legionnaire](/npc/160139) at (**y:** -6, **x:** -1191)



**Spawn NPC:**  [Condor](/npc/160138) at (**y:** 54, **x:** -1005)


elseif(count == 3) then



>**Legionnaire Claudius says:** I have been discovered! You should have left well enough alone!!!



**Stop timer** named *attack*

end
