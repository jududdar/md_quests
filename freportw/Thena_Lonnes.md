# Thena Lonnes



[Thena Lonnes](/npc/9087) is a level 35 Human Monk that spawns in [West Freeport](/zone/9).



## On NPC Spawn

**Set a timer** named *spar2* for 3 seconds


## Timer(s)

if(e.timer == "spar2") then


e.self:DoAnim(eq.ChooseRandom(1,5,6,7,11,30,45,46,47));
end

