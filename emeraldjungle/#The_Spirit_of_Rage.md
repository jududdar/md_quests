# The Spirit of Rage
## On NPC Spawn

**Set a timer** named *roar* for 1 seconds
## Timer(s)

if(e.timer == "roar") then


**Stop timer** named *roar*


**Set a timer** named *depop* for 1800 seconds


**Zone Wide Emote:** <span class="text-warning">*You here a massive creature roar, as if awakened from a deep sleep.*</span>

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The Spirit of Rage despawns.**
end

## Combat

if The Spirit of Rage enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

## On NPC Death

**Spawn NPC:**  [Omakin the Stalker](/npc/94017) at this location.