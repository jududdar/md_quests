# Sorrowsong
local loc;

## Signals

if ( e.signal == 1 ) then


loc = 1;


**Set a timer** named *move* for 10 seconds


**Sorrowsong casts:** [Sorrow Song](/spell/3011) on themselves.


**Set a timer** named *song* for 5 seconds



elseif ( e.signal == 2 ) then


**Stop timer** named *move*


e.self:SetSpecialAbility(24, 0); 


e.self:SetSpecialAbility(25, 0); 


e.self:SetSpecialAbility(35, 0); 


e.self:SetBodyType(21, false);






local boss = eq.get_entity_list():GetMobByNpcTypeID(207001); 


if ( boss and boss.valid ) then



e.self:MoveTo(boss:GetX(), boss:GetY(), boss:GetZ(), -1, true);




elseif ( e.signal == 3 ) then


**Stop timer** named *move*


e.self:SetSpecialAbility(24, 1); 


e.self:SetSpecialAbility(25, 1); 


e.self:SetSpecialAbility(35, 1); 


e.self:SetBodyType(11, false);



**Sorrowsong** clears hate list.


e.self:MoveTo(1, -1, 580, 128, true);
end

## Timer(s)


if ( e.timer == "move" ) then





if ( loc == 1 ) then



**Set a timer** named *move* for 20 seconds



e.self:MoveTo(-62, -134, 580, 0, true);



loc = 2;


elseif ( loc == 2 ) then



**Set a timer** named *move* for 20 seconds



e.self:MoveTo(64, -167, 580, 0, true);



loc = 3;


else



**Set a timer** named *move* for 25 seconds



e.self:MoveTo(1, -1, 580, 128, true);



loc = 1;





elseif ( e.timer == "song" ) then


eq.stop_timer(e.timer);


**Sorrowsong casts:** [Sorrow Song](/spell/3011) on themselves.
end

## Arrive at Waypoint Script

if ( not e.self:IsEngaged() ) then


**Sorrowsong casts:** [Sorrow Song](/spell/3011) on themselves.


**Set a timer** named *song* for 5 seconds
end

## Combat

if ( not e.joined ) then


e.self:MoveTo(1, -1, 580, 128, true);
end
