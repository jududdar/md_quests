# an enthralled outcast
rand = 0;

## Arrive at Waypoint Script

rand = math.random(1,2);

if(e.wp > 0 and e.self:GetWaypointPause() > 1) then


if(rand == 1) then



>*an enthralled outcast sniffs the air around them.  Apparently it smells an intruder.*


else



>*an enthralled outcast peers around the cavern.  You get the distinct impression it knows you're here.*

end

## Depart from Waypoint Script

if(e.wp > 0 and e.self:GetWaypointPause() > 1) then


if(rand == 1) then



>*an enthralled outcast gives an indication of indifference and goes back to searching for food.*


else



>*an enthralled outcast gives up on what ever it was looking for and goes back into the caves.*


rand = 0;
