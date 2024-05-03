# Hatchling
local MOB_TYPES = {

204475, 

204469, 

204474, 
};



## Combat

if  Hatchling enters combat  then


local r = math.random(2, 4);


for i = 1, r do



eq.spawn2(MOB_TYPES[math.random(1,3)], 0, 0, e.self:GetX() + math.random(-10, 10), e.self:GetY() + math.random(-10, 10), e.self:GetZ() + 3, 0);



**Hatchling despawns.**
end
