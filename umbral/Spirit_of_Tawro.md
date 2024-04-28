# Spirit of Tawro


## On NPC Spawn
   **Set a timer** named *depop* for 900 seconds

## Timer(s)

if(e.timer == "depop") then


**Spirit of Tawro despawns.**
end

## Combat

if Spirit of Tawro enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end
