# Hero Shrine Guardian


## Arrive at Waypoint Script


if ( e.wp == (e.self:GetWaypointMax() - 2) ) then


**Signaled to:**  [Guard Change Shouter](/npc/211073)




elseif ( e.wp == (e.self:GetWaypointMax() - 1) ) then



e.self:RemoveWaypoints();


e.self:SaveGuardSpot();
end



## Signals

if ( e.signal == e.self:GetID() ) then


**Set a timer** named *move* for 60 seconds
end



## Timer(s)

if ( e.timer == "check" ) then


if ( e.self:GetX() > 0 ) then



**Hero Shrine Guardian despawns.**




elseif ( e.timer == "move" ) then


eq.stop_timer(e.timer);


**Set a timer** named *check* for 5 seconds





e.self:MoveTo(80, 0, 7.5, -1, true);




elseif ( e.timer == "failsafe" ) then





**Set a timer** named *check* for 5 seconds


e.self:MoveTo(80, 0, 7.5, -1, true);


end
