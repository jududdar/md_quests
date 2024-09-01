# Fran Prisoal

[Fran Prisoal](/npc/200230) is a level 60 Knight of Pestilence Warrior that spawns in [The Crypt of Decay](/zone/200).

Their primary faction is [KOS](/faction/5017).

local s1, s2, s3;





## Signals

if ( e.signal == 3 ) then 

s3 = true;



if ( e.signal == 2 ) then 

s2 = true;









## On NPC Death

if ( s2 and s3 ) then

**Despawn NPC:**  [\# Carprin Deatharn](/npc/200007)

**Zone Wide Emote:** <span class="text-warning">*A scream of rage engulfs the crypt as the last vestiges of the shield of dark force surrounding Carprin Deatharn fades away.*</span>

**Spawn NPC:**  [\#Carprin Deatharn](/npc/200232) at (**y:** , **x:** )

else

**Signaled to:**  [\#Abroan Drian](/npc/200222)

**Signaled to:**  [\#Breddan Rutyl](/npc/200229)









## On NPC Spawn

s1, s2, s3 = false, false, false;

**Set a timer** named *depop* for 800 seconds







## Timer(s)

**Fran Prisoal despawns.**







## Combat

if  Fran Prisoal enters combat  then

eq.pause_timer("depop");

else

eq.resume_timer("depop");



