# The Icebound Spirit



[The Icebound Spirit](/npc/73107) is a level 55 Bear Warrior that spawns in [Permafrost Caverns](/zone/73).



## On NPC Spawn

**Set a timer** named *roar* for 1 seconds


## Timer(s)

if(e.timer == "roar") then


**Stop timer** named *roar*


**Set a timer** named *depop* for 1800 seconds


**Zone Wide Emote:** <span class="text-warning">*A large creature growls from deep within its icy lair.*</span>

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The Icebound Spirit despawns.**
end



## Combat

if The Icebound Spirit enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## On NPC Death

**Spawn NPC:**  [Zehkes the Great Storm](/npc/73007) at this location.