# Kobb
## On NPC Spawn

eq.set_timer("depop",math.random(1800000,7200000));
## Timer(s)

**Kobb despawns.**
## Combat

if Kobb enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
