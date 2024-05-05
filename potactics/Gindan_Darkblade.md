# Gindan Darkblade



[Gindan Darkblade](/npc/214032) is a level 65 Rallos Zek Minion Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).



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




**Spawn NPC:**  [Gindan Darkblade](/npc/214032) at this location.




**Spawn NPC:**  [Gindan Darkblade](/npc/214032) at this location.




**Gindan Darkblade despawns.**







elseif ( e.timer == "depop" ) then


**Gindan Darkblade despawns.**
end



## Combat

if  Gindan Darkblade enters combat  then


eq.pause_timer("depop");


if ( e.self:GetSpawnPointID() > 0 ) then



**Set a timer** named *checkhp* for 5 seconds


else


eq.resume_timer("depop");


**Stop timer** named *checkhp*
end
