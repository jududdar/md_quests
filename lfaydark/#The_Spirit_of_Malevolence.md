# The Spirit of Malevolence


## On NPC Spawn

**Set a timer** named *roar* for 1 seconds


## Timer(s)

if(e.timer == "roar") then


**Stop timer** named *roar*


**Set a timer** named *depop* for 1800 seconds


**Zone Wide Emote:** <span class="text-warning">*The air before the large monolith grows solid, as misty tendrils wrap together in the shape of a large wolf.*</span>

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The Spirit of Malevolence despawns.**
end



## Combat

if The Spirit of Malevolence enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## On NPC Death

**Spawn NPC:**  [Khaliz the Mistrunner](/npc/57006) at this location.