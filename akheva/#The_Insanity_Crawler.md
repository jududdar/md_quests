# The Insanity Crawler
## On NPC Spawn

**Zone Wide Emote:** <span class="text-warning">*You hear squealing voices of Centi echo through the dark hallways.  Something must have them frightened.  You find yourself wondering what could possibly scare the servants of the Akheva.  Do you really want to know?*</span>

**Set a timer** named *depop* for 2940 seconds
## Timer(s)

if(e.timer == "depop") then


**The Insanity Crawler despawns.**
end

## Combat

if The Insanity Crawler enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

## If NPC Kills Player



**Spawn NPC:**  [A mind worm](/npc/179003) at this location.

**Spawn NPC:**  [A mind worm](/npc/179003) at this location.

**Spawn NPC:**  [A mind worm](/npc/179003) at this location.

**Spawn NPC:**  [A mind worm](/npc/179003) at this location.

**Spawn NPC:**  [A mind worm](/npc/179003) at this location.