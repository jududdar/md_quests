# Abroan Drian
local s1, s2, s3;

## Signals

if ( e.signal == 1 ) then 


s1 = true;

if ( e.signal == 3 ) then 


s3 = true;
end

## On NPC Death

if ( s1 and s3 ) then


**Despawn NPC:**  [\# Carprin Deatharn](/npc/200007)


**Zone Wide Emote:** <span class="text-warning">*A scream of rage engulfs the crypt as the last vestiges of the shield of dark force surrounding Carprin Deatharn fades away.*</span>


**Spawn NPC:**  [\#Carprin Deatharn](/npc/200232) at this location.

else


**Signaled to:**  [\#Breddan Rutyl](/npc/200229)


**Signaled to:**  [\#Fran Prisoal](/npc/200230)
end

## On NPC Spawn

s1, s2, s3 = false, false, false;

**Set a timer** named *depop* for 800 seconds
## Timer(s)

**Abroan Drian despawns.**
## Combat

if  Abroan Drian enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end
