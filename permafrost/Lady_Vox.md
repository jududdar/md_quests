# Lady Vox


local SpawnX = 0;
local SpawnY = 0;
local SpawnZ = 0;
local SpawnH = 0;



## On NPC Spawn

SpawnX = e.self:GetX();

SpawnY = e.self:GetY();

SpawnZ = e.self:GetZ();

SpawnH = e.self:GetHeading();

local range = 210;

local range2 = 98;

eq.set_proximity(SpawnX - range, SpawnX + range, SpawnY - range2, SpawnY + range, SpawnZ - 20, SpawnZ + 50);
function event_enter(e)

if(**Your level** > 52 and e.other:Admin() < 80) then


**Message:** <span class="text-warning">*I will not fight you, but I shall banish you!*</span>


e.other:MovePC(30,-7024,2020,-60.7,0); 
end



## Combat

if Lady Vox enters combat  then


**Set a timer** named *1* for 1 seconds

else


**Stop timer** named *1*


e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);
end



## Timer(s)

if(e.timer == "1") then


if(e.self:GetX() < -431 or e.self:GetX() > -85 or e.self:GetY() < 770 or e.self:GetY() > 1090 or e.self:GetZ()  < -50) then



e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);


elseif(e.self:CountHateList() > 0) then



e.self:ForeachHateList(




function(ent, hate, damage, frenzy)





if(ent:IsClient()) then






ent:CastToClient():Message(4,"I will not fight you, but I shall banish you!");






if(ent:CastToClient():GetBindZoneID() == 73) then







ent:CastToClient():SetBindPoint(30,-7024,2020,-60);











ent:CastToClient():MovePC(30,-7024,2020,-60.7,0);












function(ent, hate, damage, frenzy)





if(ent:IsClient()) then






if(ent:CastToClient():GetLevel() > 52) then







return true;














return false;






);

end



## Signals

if ( e.signal == 1 ) then


**Lady Vox shouts:** <span class="text-danger">The Sleeper stirs!  A glorious new age for Norrath is about to begin, and my exile is about to</span>
end
