# a lightcrawler



[a lightcrawler](/npc/159109) is a level 38 Lightcrawler Warrior that spawns in [Sanctus Seru](/zone/159).



## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Combat

if a lightcrawler enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)

if(e.timer == "depop") then


**a lightcrawler despawns.**
end