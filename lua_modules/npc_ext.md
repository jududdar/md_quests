# npc ext





function NPC:ForeachHateList(func, cond)

cond = cond or function(ent, hate, damage, frenzy) return true

local lst = self:GetHateList();

for ent in lst.entries do


local cv = cond(ent.ent, ent.hate, ent.damage, ent.frenzy);


if(cv) then



func(ent.ent, ent.hate, ent.damage, ent.frenzy);

end

function NPC:CountHateList(cond)

cond = cond or function(ent, hate, damage, frenzy) return true

local lst = self:GetHateList();

local ret = 0;

for ent in lst.entries do


local cv = cond(ent.ent, ent.hate, ent.damage, ent.frenzy);


if(cv) then



ret = ret + 1;




return ret;

function NPC:CheckGround(range)



local id, ix, iy, iz;

local sx, sy, sz = self:GetX(), self:GetY(), self:GetZ();


local olist = eq.get_entity_list():GetObjectList();

range = tonumber(range) or 25;



for obj in olist.entries do




ix, iy, iz = obj:GetX(), obj:GetY(), obj:GetZ();


if ( obj:GetItemID() > 0



and ix - sx < range and ix - sx > -range



and iy - sy < range and iy - sy > -range



and iz - sz < range and iz - sz > -range


) then



obj:DepopWithTimer();



return true;


return false;