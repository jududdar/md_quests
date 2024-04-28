# Heratius Grolden
## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds
## Timer(s)

if(e.timer == "depop") then


**Heratius Grolden despawns.**
end

## Combat

if Heratius Grolden enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

## On NPC Death
   **Spawn NPC:**  [\#Valdanov Zevfeer](/npc/172014) at (**y:** 576, **x:** -1425)
end