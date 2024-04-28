# Gindan Blademaster
## On NPC Spawn

if ( e.self:GetSpawnPointID() == 0 ) then 


**Set a timer** named *depop* for 360 seconds


e.self:SetSpecialAbility(49, 1);

end

## Timer(s)


if ( e.timer == "checkhp" ) then




if ( e.self:GetHPRatio() < 50 ) then



if ( math.random(100) < 25 ) then





eq.stop_timer(e.timer);



else




**Spawn NPC:**  [Gindan Blademaster](/npc/214031) at this location.




**Spawn NPC:**  [Gindan Blademaster](/npc/214031) at this location.




**Gindan Blademaster despawns.**







elseif ( e.timer == "depop" ) then


**Gindan Blademaster despawns.**
end

## Combat

if  Gindan Blademaster enters combat  then


eq.pause_timer("depop");


if ( e.self:GetSpawnPointID() > 0 ) then



**Set a timer** named *checkhp* for 5 seconds


else


eq.resume_timer("depop");


**Stop timer** named *checkhp*
end
