# croc trigger
local CrocUp = 0;



## On NPC Spawn

croc_spawns();
function croc_spawns()

local RandomCroc = 65134;

local RandomNumber = 0;

RandomNumber = math.random(100);



if(RandomNumber <=45) then


eq.spawn2(RandomCroc,0,0,470,1661,-70,66);


eq.spawn2(RandomCroc,0,0,462,1653,-70,66);


CrocUp = 2;

elseif(RandomNumber > 45 and RandomNumber <= 73) then


eq.spawn2(RandomCroc,0,0,470,1661,-70,66);


eq.spawn2(RandomCroc,0,0,462,1653,-70,66);


eq.spawn2(RandomCroc,0,0,450,1661,-70,66);


CrocUp = 3;

elseif(RandomNumber > 73 and RandomNumber <= 85) then


eq.spawn2(RandomCroc,0,0,470,1661,-70,66);


CrocUp = 1;

elseif(RandomNumber > 85 and RandomNumber <= 95) then


**Spawn NPC:**  [an ancient croc](/npc/65139) at (**y:** 1653, **x:** 462)


CrocUp = 1;

elseif(RandomNumber > 95 and RandomNumber <= 98) then


eq.spawn2(RandomCroc,0,0,470,1661,-70,66);


eq.spawn2(RandomCroc,0,0,462,1653,-70,66);


eq.spawn2(RandomCroc,0,0,450,1661,-70,66);


eq.spawn2(RandomCroc,0,0,459,1671,-70,66); 


CrocUp = 4;

elseif(RandomNumber > 98) then


eq.spawn2(RandomCroc,0,0,470,1661,-70,66);


eq.spawn2(RandomCroc,0,0,462,1653,-70,66);


eq.spawn2(RandomCroc,0,0,450,1661,-70,66);


eq.spawn2(RandomCroc,0,0,459,1671,-70,66); 


eq.spawn2(RandomCroc,0,0,480,1667,-70,66); 


CrocUp = 5;
end



## Signals

CrocUp = CrocUp - 1;

if(CrocUp == 0) then


**Set a timer** named *spawn timer* for 487 seconds
end



## Timer(s)

if(e.timer == "spawn timer") then


croc_spawns();


**Stop timer** named *spawn timer*
end
