# mob ext
function Mob:ForeachHateList(func, cond)

cond = cond or function(ent, hate, damage, frenzy) return true

local lst = self:GetHateList();

for ent in lst.entries do


local cv = cond(ent.ent, ent.hate, ent.damage, ent.frenzy);


if(cv) then



func(ent.ent, ent.hate, ent.damage, ent.frenzy);

end

function Mob:CountHateList(cond)

cond = cond or function(ent, hate, damage, frenzy) return true

local lst = self:GetHateList();

local ret = 0;

for ent in lst.entries do


local cv = cond(ent.ent, ent.hate, ent.damage, ent.frenzy);


if(cv) then



ret = ret + 1;




return ret;