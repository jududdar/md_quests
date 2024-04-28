# Atlaar Mignar
local n;

## Signals

if ( e.signal == 1 ) then


**Stop timer** named *animate*


>**Atlaar Mignar says:** Yes sir! Sergeant Bryson, sir!


e.self:MoveTo(-1337, 190, 7.5, 65, true);




elseif ( e.signal == 2 ) then


>**Atlaar Mignar says:** Yes sir! Sergeant Bryson, sir!


**Set a timer** named *move* for 5 seconds




elseif ( e.signal == 3 ) then


>**Atlaar Mignar says:** Sir! Yes, sir!




elseif ( e.signal == 5 ) then


>**Atlaar Mignar says:** Let us spar!


**Set a timer** named *animate* for 0 seconds
end

## Timer(s)



if ( e.timer == "animate" ) then


eq.set_timer(e.timer, 120000);


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


e.self:MoveTo(-1349, 148, 7.5, 9, true);
end
