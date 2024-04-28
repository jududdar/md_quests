# Aten Ha Ra
local WARDER_TYPES = { 158418, 158409, 158405, 158399, 158393 };

local checks = 0;

function IsWarderUp()

for _, id in ipairs(WARDER_TYPES) do


if ( eq.get_entity_list():IsMobSpawnedByNpcTypeID(id) ) then



return true;


return false;
function Warp(mob)

mob:GMMove(1412, 0, 245.5, 195.8);

mob:BuffFadeAll();

mob:WipeHateList();

checks = 0;
## Timer(s)


if ( e.self:GetZ() < 229 or e.self:GetZ() > 260 ) then


Warp(e.self);


return;



if ( e.self:IsEngaged() ) then




if ( IsWarderUp() and e.self:GetTarget().valid and e.self:GetTarget():IsClient() and not e.self:GetTarget():CastToClient():GetGM() ) then



e.self:CastSpell(2859, e.self:GetTarget():GetID()); 



return;











if ( e.self:GetTarget():IsWarriorClass() and e.self:CombatRange(e.self:GetTarget())
and not e.self:CheckLoS(e.self:GetTarget())
) then






checks = checks + 1;



if ( checks > 3 ) then




Warp(e.self);




else



checks = 0;

end

## On NPC Spawn

**Set a timer** named *sploitcheck* for 5 seconds