# Ran\`un



[Ran\`un](/npc/9027) is a level 35 Human Monk that spawns in [West Freeport](/zone/9).



## On NPC Spawn

**Set a timer** named *spar1* for 5 seconds


## Timer(s)

if(e.timer == "spar1") then


e.self:DoAnim(eq.ChooseRandom(1,5,6,7,11,30,45,46,47));
end

