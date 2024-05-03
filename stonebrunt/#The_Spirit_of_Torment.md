# The Spirit of Torment


## On NPC Spawn

**Set a timer** named *roar* for 1 seconds


## Timer(s)

if(e.timer == "roar") then


**Stop timer** named *roar*


**Set a timer** named *depop* for 1800 seconds


**Zone Wide Emote:** <span class="text-warning">*Something glows brightly from high above the falls.*</span>

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The Spirit of Torment despawns.**
end



## Combat

if The Spirit of Torment enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## On NPC Death

**Spawn NPC:**  [Sharik the Watcher](/npc/100024) at this location.