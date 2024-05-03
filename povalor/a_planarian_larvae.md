# a planarian larvae



local x, y, z;
local spawnLocs = {};



## On NPC Spawn

eq.set_timer("move", 24000 + math.random(1000, 5000));

spawnLocs[e.self:GetID()] = { x = e.self:GetX(), y = e.self:GetY(), z = e.self:GetZ() }


## Combat

if  a planarian larvae enters combat  then


eq.pause_timer("move");


eq.pause_timer("burrow");

else


eq.resume_timer("move");


eq.resume_timer("burrow");
end

function event_death(e)

spawnLocs[e.self:GetID()] = nil;


## Timer(s)

if ( e.self:Charmed() ) then


return;



local l = spawnLocs[e.self:GetID()];



if ( e.timer == "move" ) then


if ( l.b == 1 ) then



e.self:MoveTo(l.bx + math.random(-1, 1), l.by + math.random(-1, 1), e.self:GetZ(), -1, false); 


elseif ( math.random(1, 5) == 1 ) then



eq.stop_timer(e.timer);



**Set a timer** named *move* for 0 seconds



**Set a timer** named *burrow* for 7 seconds



l.bx = e.self:GetX();



l.by = e.self:GetY();



e.self:MoveTo(l.bx + math.random(-1, 1), l.by + math.random(-1, 1), e.self:GetZ(), -1, false); 



l.b = 1;


else



e.self:MoveTo(l.x + math.random(-20, 20), l.y + math.random(-20, 20), l.z, -1, true);





elseif ( e.timer == "burrow" ) then


if ( l.b == 1 ) then



eq.stop_timer(e.timer);



**Stop timer** named *move*



**Set a timer** named *burrow* for 40 seconds



e.self:GMMove(3000, 3000, 0, 0, true, true); 



l.b = 2;


elseif ( l.b == 2 ) then



eq.stop_timer(e.timer);



e.self:GMMove(l.x, l.y, l.z, math.random(0, 255), true, true); 



eq.set_timer("move", 24000 + math.random(1000, 5000));



l.b = nil;

end
