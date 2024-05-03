# Breddan Rutyl
local s1, s2, s3;



## Signals

if ( e.signal == 1 ) then 


s1 = true;

if ( e.signal == 2 ) then 


s2 = true;
end



## On NPC Death

if ( s1 and s2 ) then


**Despawn NPC:**  [\# Carprin Deatharn](/npc/200007)


**Zone Wide Emote:** <span class="text-warning">*A scream of rage engulfs the crypt as the last vestiges of the shield of dark force surrounding Carprin Deatharn fades away.*</span>


**Spawn NPC:**  [\#Carprin Deatharn](/npc/200232) at this location.

else


**Signaled to:**  [\#Abroan Drian](/npc/200222)


**Signaled to:**  [\#Fran Prisoal](/npc/200230)
end



## On NPC Spawn

s1, s2, s3 = false, false, false;

**Set a timer** named *depop* for 800 seconds


## Timer(s)

**Breddan Rutyl despawns.**


## Combat

if  Breddan Rutyl enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
