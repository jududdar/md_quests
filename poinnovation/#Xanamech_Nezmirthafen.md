# Xanamech Nezmirthafen



[Xanamech Nezmirthafen](/npc/206208) is a level 66 Dragon Warrior that spawns in [Plane of Innovation](/zone/206).



## Signals

if ( e.signal == 1 ) then


e.self:SetAppearance(0);


**Set a timer** named *wake* for 3 seconds
end



## On NPC Spawn

**Set a timer** named *lie* for 0 seconds

**Set a timer** named *depop* for 1800 seconds


## Timer(s)


eq.stop_timer(e.timer);



if ( e.timer == "depop" ) then


**Xanamech Nezmirthafen despawns.**




elseif ( e.timer == "lie" ) then


e.self:SetAppearance(1);




elseif ( e.timer == "wake" ) then


e.self:SetSpecialAbility(24, 0); 


e.self:SetSpecialAbility(25, 0); 


e.self:SetSpecialAbility(35, 0); 


e.self:SetBodyType(5, false); 
end



## Combat

if  Xanamech Nezmirthafen enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## On NPC Death

**Signaled to:**  [Nitram Anizok](/npc/206033)