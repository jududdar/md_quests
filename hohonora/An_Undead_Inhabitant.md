# An Undead Inhabitant

[An Undead Inhabitant](/npc/211043) is a level 66 Animated Armor Shadow Knight that spawns in [Halls of Honor](/zone/211).

Their primary faction is [Beta KOS](/faction/479).

## On NPC Death
local x, y, z, h = e.self:GetX(), e.self:GetY(), e.self:GetZ(), e.self:GetHeading();
eq.spawn2(211081, 0, 0, x, y, z, h); 
eq.spawn2(211081, 0, 0, x, y, z, h); 
