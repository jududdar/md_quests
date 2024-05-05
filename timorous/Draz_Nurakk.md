# Draz Nurakk



[Draz Nurakk](/npc/96003) is a level 55 Iksar Beastlord that spawns in [Timorous Deep](/zone/96).



## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds


## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


**Draz Nurakk despawns.**
end



## Combat

if Draz Nurakk enters combat  then


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## On NPC Death

**Spawn NPC:**  [Draz Nurakks Image](/npc/96010) at (**y:** -9170, **x:** 1985)

**Spawn NPC:**  [Draz Nurakks Image](/npc/96010) at (**y:** -9204, **x:** 1986)

**Spawn NPC:**  [Draz Nurakks Image](/npc/96010) at (**y:** -9204, **x:** 1958)

**Spawn NPC:**  [Draz Nurakks Image](/npc/96010) at (**y:** -9218, **x:** 1975)

**Spawn NPC:**  [Draz Nurakks Image](/npc/96010) at (**y:** -9214, **x:** 2009)

**Spawn NPC:**  [Draz Nurakks Image](/npc/96010) at (**y:** -9181, **x:** 2004)