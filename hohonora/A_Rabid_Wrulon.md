# A Rabid Wrulon



[A Rabid Wrulon](/npc/211044) is a level 66 Wrulon Warrior that spawns in [Halls of Honor](/zone/211).



## On NPC Death

local x, y, z, h = e.self:GetX(), e.self:GetY(), e.self:GetZ(), e.self:GetHeading();

eq.spawn2(211080, 0, 0, x, y, z, h); 

eq.spawn2(211080, 0, 0, x, y, z, h); 