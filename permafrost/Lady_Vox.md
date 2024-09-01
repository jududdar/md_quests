# Lady Vox

[Lady Vox](/npc/73057) is a level 55 Dragon Cleric that spawns in [Permafrost Caverns](/zone/73).

Their primary faction is [Vox](/faction/319).local SpawnX = 0;
local SpawnY = 0;
local SpawnZ = 0;
local SpawnH = 0;



## On NPC Spawn
SpawnX = e.self:GetX();
SpawnY = e.self:GetY();
SpawnZ = e.self:GetZ();
SpawnH = e.self:GetHeading();




## Combat
if Lady Vox enters combat  then
**Set a timer** named *1* for 1 seconds
else
**Stop timer** named *1*
e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);





## Timer(s)
if(e.timer == "1") then
if(e.self:GetX() < -431 or e.self:GetX() > -85 or e.self:GetY() < 770 or e.self:GetY() > 1090 or e.self:GetZ()  < -50) then
e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);






## Signals
if ( e.signal == 1 ) then
**Lady Vox shouts:** <span class="text-danger">The Sleeper stirs!  A glorious new age for Norrath is about to begin, and my exile is about to end!</span>

