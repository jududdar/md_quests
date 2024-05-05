# Grummus



[Grummus](/npc/205091) is a level 70 Diseased Fiend Warrior that spawns in [Plane of Disease](/zone/205).

local PLANAR_PROJECTION_TYPE = 205156;



## On NPC Death

eq.spawn2(PLANAR_PROJECTION_TYPE, 0, 0, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0);

eq.signal(PLANAR_PROJECTION_TYPE, e.killer:GetID()); 