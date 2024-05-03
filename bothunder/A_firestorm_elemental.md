# A firestorm elemental


## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A firestorm elemental despawns.**
end



## Combat

if  A firestorm elemental enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");





if ( e.self:GetZ() > 1700 and e.self:Charmed() ) then


e.self:BuffFadeByEffect(22);


e.self:ModifyNPCStat("mr", "200");
end
