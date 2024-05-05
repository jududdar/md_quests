# The Spirit of Sorrow



[The Spirit of Sorrow](/npc/83244) is a level 55 Alligator Warrior that spawns in [Swamp of No Hope](/zone/83).



## On NPC Spawn

**Set a timer** named *roar* for 1 seconds


## Timer(s)

if(e.timer == "roar") then


**Stop timer** named *roar*


**Set a timer** named *depop* for 1800 seconds


**Zone Wide Emote:** <span class="text-warning">*A giant reptile roars, as it sinks below the surface of the pond. It appears that is senses your approach.*</span>

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The Spirit of Sorrow despawns.**
end



## Combat

if The Spirit of Sorrow enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## On NPC Death

**Spawn NPC:**  [Herikol the Lurker](/npc/83056) at this location.