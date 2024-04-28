# The Spirit of Decay
## On NPC Spawn

**Set a timer** named *roar* for 1 seconds
## Timer(s)

if(e.timer == "roar") then


**Stop timer** named *roar*


**Set a timer** named *depop* for 1800 seconds


**Zone Wide Emote:** <span class="text-warning">*A large yellow spider drifts down from the jungle canopy. Perhaps it senses the proximity of its next meal.*</span>

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The Spirit of Decay despawns.**
end

## Combat

if The Spirit of Decay enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

## On NPC Death

**Spawn NPC:**  [Yekan the Weaver](/npc/47005) at this location.