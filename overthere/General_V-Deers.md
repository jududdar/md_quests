# General V\`Deers



[General V\`Deers](/npc/93087) is a level 58 Dark Elf Shadow Knight that spawns in [The Overthere](/zone/93).



## Signals

if(e.signal==1) then


>**General V-Deers says:** Fall out and report to your guard posts.


eq.stop();


e.self:MoveTo(2139,2675,-49,72,true);

elseif(e.signal==2) then


e.self:MoveTo(2717,2500,-49,65,true);


**Set a timer** named *getset* for 525 seconds
end



## Timer(s)

if(e.timer == "getset") then


**Stop timer** named *getset*


>**General V-Deers says:** Dragoons!!  Attention!!  Right face!!


eq.start(8);
end



## Arrive at Waypoint Script

if(e.wp==1) then


>**General V-Deers says:** Forward.. march!!  Your left.. Your.. left, right, march!  Eighty.. second.. dragoon soldier!!  Pick up your weapon and follow me!!


**Signaled to:** 93186


**Signaled to:**  [Dragoon Barber W\`Selo](/npc/93124)


**Signaled to:**  [Dragoon TVem](/npc/93024)


**Signaled to:**  [Dragoon T\`Vex](/npc/93084)


**Signaled to:**  [Dragoon V\`Lask](/npc/93125)


**Signaled to:**  [Dragoon V\`Resh](/npc/93086)
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





