# Spirit of Tawro

[Spirit of Tawro](/npc/176020) is a level 60 Elemental Warrior that spawns in [The Umbral Plains](/zone/176).

Their primary faction is [KOS](/faction/5017).





## On NPC Spawn

**Set a timer** named *depop* for 900 seconds







## Timer(s)

if(e.timer == "depop") then

**Spirit of Tawro despawns.**









## Combat

if Spirit of Tawro enters combat  then

if(not eq.is_paused_timer("depop")) then

eq.pause_timer("depop");



else

eq.resume_timer("depop");



