# a coterie assassin



[a coterie assassin](/npc/160230) is a level 38 Vampire Warrior that spawns in [Katta Castellum](/zone/160).



## On NPC Spawn

eq.set_timer("depop",math.random(300000,1200000));


## Timer(s)

if(e.timer == "depop") then


**a coterie assassin despawns.**
end



## Combat

if a coterie assassin enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
