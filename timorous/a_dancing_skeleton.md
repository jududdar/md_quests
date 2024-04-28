# a dancing skeleton
## Dialog

**You say:** `gomoz`



>*a dancing skeleton stops in suprise.*


>**a dancing skeleton says:** Gomoz!! Why, that is me! I was heading off to be with the elements when I was captured by this smelly ogre. Actually, he is not as smelly as most.


eq.stop_timer(10);


eq.stop_timer(11);


eq.stop_timer(12);


eq.stop_timer(100);


eq.set_timer(100,40000); 

**You say:** `talon southpaw`



>**a dancing skeleton says:** Master Talon Southpaw!! He was my master. Dead, he became. Off to the elements. I keep his special hand with me. Perhaps I should have it returned. Maybe I shall find a young adventurer to [return the hand to Cabilis].


eq.stop_timer(100);


eq.set_timer(100,30000); 

**You say:** `return the hand to cabilis`



>**a dancing skeleton says:** Yes!! Return the hand. Here it is. Missing four it is. Within the tower of past pain and torture is where the four lie. Taken by bones similar to myself.


**You receive:**  [hand with one only a thumb](/item/17037)


eq.set_timer(100,4000);
end

## Signals

if(e.signal == 5) then


eq.set_timer(10,2000); 


>*a dancing skeleton shambles to its feet and begins to jig somewhat grudingly.*
end

## Timer(s)

if(e.timer == 10) then





eq.stop_timer(10);


eq.set_timer(11,2000);


e.self:DoAnim(58);

if(e.timer == 11) then





eq.stop_timer(11);


eq.set_timer(12,2000);


e.self:DoAnim(45);

if(e.timer == 12) then





eq.stop_timer(12);


eq.set_timer(13,2000);


e.self:DoAnim(58);

if(e.timer == 13) then





eq.stop_timer(13);


eq.set_timer(100,2000);


e.self:DoAnim(16);

if(e.timer == 100) then





eq.stop_timer(100);


**a dancing skeleton despawns.**
end

## Turn-Ins



**This NPC *should* return incorrect items given.**













