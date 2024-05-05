# a ghastly apparition



[a ghastly apparition](/npc/160007) is a level 38 Zombie Warrior that spawns in [Katta Castellum](/zone/160).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Timer(s)

if(e.timer == "depop") then


**a ghastly apparition despawns.**
end



## Combat

if a ghastly apparition enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
