# a swarm


## Combat



if  a swarm enters combat  then





local typ;


if ( e.self:GetZ() > -200 ) then







typ = eq.ChooseRandom(216255, 216252, 216250, 216249, 216264);


else



typ = eq.ChooseRandom(216254, 216253, 216251); 






local roll = math.random(2, 4);


for i = 1, roll do



eq.spawn2(typ, 0, 0, e.self:GetX() + math.random(-5, 5), e.self:GetY() + math.random(-5, 5), e.self:GetZ(), 0);



**a swarm despawns.**
end
