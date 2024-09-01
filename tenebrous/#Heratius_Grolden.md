# Heratius Grolden

[Heratius Grolden](/npc/172013) is a level 58 Vampire Shadow Knight that spawns in [The Tenebrous Mountains](/zone/172).

Their primary faction is [Coterie of the Eternal Night](/faction/1506).



## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds







## Timer(s)

if(e.timer == "depop") then

**Heratius Grolden despawns.**









## Combat

if Heratius Grolden enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");









## On NPC Death

**Spawn NPC:**  [\#Valdanov Zevfeer](/npc/172014) at (**y:** 576, **x:** -1425)

