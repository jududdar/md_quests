# Templar Tingar



[Templar Tingar](/npc/115200) is a level 40 Coldain Warrior that spawns in [The City of Thurgadin](/zone/115).





## On NPC Spawn

**Set a timer** named *talk* for 480 seconds


## Timer(s)

local count = 0;

if(e.timer == "talk") then


count = count + 1;


if(count == 1) then



>**Templar Tingar says:** Oh Brell, what ever did I do to inspire your wrath?


elseif(count == 2) then



>**Templar Tingar says:** Ok, let's try this again.



>**Templar Tingar says:** ROYGHT FACE!



count = 0;

end
