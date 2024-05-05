# Eldon Starkorp



[Eldon Starkorp](/npc/211038) is a level 60 Human Warrior that spawns in [Halls of Honor](/zone/211).

local n;



## Signals

if ( e.signal == 1 ) then


**Stop timer** named *animate*


>**Eldon Starkorp says:** Yes sir! Sergeant Bryson, sir!


e.self:MoveTo(-1337, 130, 7.5, 65, true);




elseif ( e.signal == 3 ) then


>**Eldon Starkorp says:** Sir! Yes, sir!






elseif ( e.signal == 4 ) then


>**Eldon Starkorp says:** Yes sir! Sergeant Bryson, sir!


**Set a timer** named *move* for 5 seconds




elseif ( e.signal == 5 ) then


>**Eldon Starkorp says:** Let us spar!


**Set a timer** named *animate* for 2 seconds
end



## Timer(s)



if ( e.timer == "animate" ) then


eq.set_timer(e.timer, 42000);


**Set a timer** named *doanim* for 3 seconds


n = 0;



elseif ( e.timer == "doanim" ) then


n = n + 1;





local anim = 1;


if ( n == 2 ) then



anim = 3;


elseif ( n == 3 ) then



anim = 11;


elseif ( n == 4 ) then



anim = 7;



eq.stop_timer(e.timer);



e.self:DoAnim(anim);



elseif ( e.timer == "move" ) then


eq.stop_timer(e.timer);


e.self:MoveTo(-1291, 223, 7.5, 167, true);
end
