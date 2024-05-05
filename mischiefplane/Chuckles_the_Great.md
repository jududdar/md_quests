# Chuckles the Great



[Chuckles the Great](/npc/126281) is a level 55 Ratman Warrior that spawns in [Plane of Mischief](/zone/126).



## On NPC Spawn

**Set a timer** named *dance* for 1 seconds


## Timer(s)

if(e.timer == "dance") then


e.self:DoAnim(34);  
end



## Combat

if Chuckles the Great enters combat  then


if(not eq.is_paused_timer("dance")) then



eq.pause_timer("dance");


else


eq.resume_timer("dance");
end
