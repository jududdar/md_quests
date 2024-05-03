# An Enthralled Razorfiend
rand = 0;



## Arrive at Waypoint Script

rand = math.random(1,2);

if(e.wp > 0 and e.self:GetWaypointPause() > 1) then


if(rand == 1) then



>*An Enthralled Razorfiend nibbles on a small mushroom at its feet.*


else



>*An Enthralled Razorfiend peers around the cavern.  You get the distinct impression it knows you're here.*

end



## Depart from Waypoint Script

if(e.wp > 0 and e.self:GetWaypointPause() > 1) then


if(rand == 1) then



>*An Enthralled Razorfiend finishes feeding and moves on.*


else



>*An Enthralled Razorfiend gives up on what ever it was looking for and goes back into the caves.*


rand = 0;
