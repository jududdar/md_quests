# Wraith of Domagr

[Wraith of Domagr](/npc/201517) is a level 44 Banshee Warrior that spawns in [Plane of Justice](/zone/201).

Their primary faction is [KOS](/faction/5017).



## On NPC Spawn

**Set a timer** named *depop* for 200 seconds







## Timer(s)

**Wraith of Domagr despawns.**







## Combat

if  Wraith of Domagr enters combat  then

eq.pause_timer("depop");

else

eq.resume_timer("depop");



