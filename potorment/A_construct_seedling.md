# A construct seedling


## On NPC Spawn

**Set a timer** named *depop* for 100 seconds

**Set a timer** named *move* for 0 seconds


## Timer(s)


if ( e.timer == "move" and not e.self:IsEngaged() ) then


**Set a timer** named *move* for 6 seconds





local boss = eq.get_entity_list():GetMobByNpcTypeID(207003); 


if ( not boss or not boss.valid ) then



**A construct seedling despawns.**



e.self:MoveTo(boss:GetX(), boss:GetY(), boss:GetZ() - 5.5, -1, true);


elseif ( e.timer == "depop" ) then


**A construct seedling despawns.**



## Combat

if  A construct seedling enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end