# The Acolyte of Affliction
## Combat

if  The Acolyte of Affliction enters combat  then


**Set a timer** named *adds* for 50 seconds

else


**Stop timer** named *adds*
end

## Timer(s)


if ( e.timer == "adds" ) then




local x = math.random(5, 10);


for i = 1, x do



eq.spawn2( [A construct seedling](/npc/207295), 0, 0, math.random(-32, 32), math.random(-175, -153), 194, 0); 

end

## On NPC Death

**Despawn all instances of:**  [A construct seedling](/npc/207295)