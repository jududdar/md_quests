# Lord Pickclaw
## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds
## Timer(s)

**Lord Pickclaw despawns.**
## Combat

if Lord Pickclaw enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end