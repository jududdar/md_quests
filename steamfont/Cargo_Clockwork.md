# Cargo Clockwork



[Cargo Clockwork](/npc/56105) is a level 30 Spider Warrior that spawns in [Steamfont Mountains](/zone/56).

local delivery = 0;



## Signals

local qglobal = eq.get_qglobals();


if(e.signal == 1) then


>*Cargo Clockwork Chuga.. Chug..Chug.. 'This unit requires maintenance.'*

elseif(e.signal == 2) then


if(qglobal["CargoClockwork"] == nil) then



eq.set_global("CargoClockwork","1",7,"H2");



eq.start(5); 


end



## Depart from Waypoint Script

if(e.wp == 1) then


if(delivery == 1) then



eq.stop();



delivery = 0;


elseif(e.wp == 8) then


>**Cargo Clockwork says:** kachunk .. kachunk..


**Signaled to:**  [Watchman Halv](/npc/56155)

elseif(e.wp == 10) then


if(delivery == 0) then



delivery = 1;



>*Cargo Clockwork Chuga.. Chug..Chug..*



>*Cargo Clockwork The chugging of the Cargo Clockwork comes to a halt.*



**Spawn NPC:**  [Hector the highway bandit](/npc/56178) at (**y:** -700, **x:** 30)



**Spawn NPC:**  [Renaldo the highway bandit](/npc/56179) at (**y:** -732, **x:** 95)



**Spawn NPC:**  [Jerald the highway bandit](/npc/56180) at (**y:** -615, **x:** 53)



>**Cargo Clockwork says:** This is highway robbery.

end



## On NPC Death

delivery = 0;

**Signaled to:**  [Hector the highway bandit](/npc/56178)

**Signaled to:**  [Renaldo the highway bandit](/npc/56179)

**Signaled to:**  [Jerald the highway bandit](/npc/56180)