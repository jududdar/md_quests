# Eenot



[Eenot](/npc/20276) is a level 18 Tiger Druid that spawns in [Kithicor Forest](/zone/20).



## On NPC Spawn

eq.set_timer("depop",math.random(10000,7200000));


## Timer(s)

**Eenot despawns.**


## Combat

if Eenot enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
