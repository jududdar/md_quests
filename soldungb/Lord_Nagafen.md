# Lord Nagafen

[Lord Nagafen](/npc/32040) is a level 55 Dragon Warrior that spawns in [Nagafen's Lair](/zone/32).

Their primary faction is [Nagafen](/faction/249).

local SpawnX = 0;

local SpawnY = 0;

local SpawnZ = 0;

local SpawnH = 0;





## On NPC Spawn

SpawnX = e.self:GetX();

SpawnY = e.self:GetY();

SpawnZ = e.self:GetZ();

SpawnH = e.self:GetHeading();







## Combat

if Lord Nagafen enters combat  then

**Set a timer** named *1* for 1 seconds

else

**Stop timer** named *1*

e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);









## Timer(s)

if(e.timer == "1") then

if(e.self:GetX() < -1000 or e.self:GetX() > -650 or e.self:GetY() < -1500 or e.self:GetY() > -1170) then

e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);











## Signals

if ( e.signal == 1 ) then

**Lord Nagafen shouts:** <span class="text-danger">Ha!  The Ring and Claws are doomed!  The Sleeper has been awakened, what a glorious day!  Lady Vox, I will see you soon, our long delayed nuptials can now proceed!</span>



