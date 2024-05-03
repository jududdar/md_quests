# Lord Nagafen


local SpawnX = 0;
local SpawnY = 0;
local SpawnZ = 0;
local SpawnH = 0;



## On NPC Spawn

SpawnX = e.self:GetX();

SpawnY = e.self:GetY();

SpawnZ = e.self:GetZ();

SpawnH = e.self:GetHeading();

local range = 230;

eq.set_proximity(SpawnX - range, SpawnX + range, SpawnY - range, SpawnY + range);
function event_enter(e)

if(**Your level** > 52 and e.other:Admin() < 80) then


**Message:** <span class="text-warning">*I will not fight you, but I shall banish you!*</span>


e.other:MovePC(27,534,913,55,0); 
end



## Combat

if Lord Nagafen enters combat  then


**Set a timer** named *1* for 1 seconds

else


**Stop timer** named *1*


e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);
end



## Timer(s)

if(e.timer == "1") then


if(e.self:GetX() < -1000 or e.self:GetX() > -650 or e.self:GetY() < -1500 or e.self:GetY() > -1170) then



e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);


elseif(e.self:CountHateList() > 0) then



e.self:ForeachHateList(




function(ent, hate, damage, frenzy)





if(ent:IsClient()) then






ent:CastToClient():Message(4,"I will not fight you, but I shall banish you!");






if(ent:CastToClient():GetBindZoneID() == 32) then







ent:CastToClient():SetBindPoint(27,534,913,55);











ent:CastToClient():MovePC(27,534,913,55,0);












function(ent, hate, damage, frenzy)





if(ent:IsClient()) then






if(ent:CastToClient():GetLevel() > 52) then







return true;














return false;






);

end



## Signals

if ( e.signal == 1 ) then


**Lord Nagafen shouts:** <span class="text-danger">Ha!  The Ring and Claws are doomed!  The Sleeper has been awakened, what a glorious day!  Lady Vox, I will see you soon, our long delayed nuptials can now proceed!</span>
end
