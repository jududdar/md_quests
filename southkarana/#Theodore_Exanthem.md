# Theodore Exanthem

## On NPC Spawn

**Signaled to:**  [an interrogator](/npc/14050)
## Signals

if(e.signal == 1) then


eq.move_to(-2750,-5465,00,192,true);


**Signaled to:**  [an interrogator](/npc/14050)

elseif(e.signal == 2) then


>**Theodore Exanthem says:** What a joke! I'm not telling you a thing. You don't look like you could scare a moss snake. I'm not afraid of you!


**Signaled to:**  [an interrogator](/npc/14050)

elseif(e.signal == 3) then


>*Theodore Exanthem reels back, his eyes wide with shock. 'Ow,' he says nervously.*


**Signaled to:**  [an interrogator](/npc/14050)

elseif(e.signal == 4) then


>*Theodore Exanthem winces and says, 'Oh. Yeah right. Like I'm afraid of that moron or something.' Theodore glances nervously over at you*


**Signaled to:**  [an interrogator](/npc/14050)

elseif(e.signal == 5) then


>*Theodore Exanthem gulps nervously*

elseif(e.signal == 6) then


>**Theodore Exanthem says:** Fine, follow me creeps.


eq.move_to(-3098,- [Fanged Talisman](/item/5872),94,160,true);




elseif(e.signal == 7) then


>**Theodore Exanthem says:** There... They are hiding out just down the hill here... Now release me!


**Signaled to:**  [an interrogator](/npc/14050)
end

## Combat

if(e.joined == true) then


**Set a timer** named *defeat* for 3 seconds
end

## Timer(s)

if(e.timer == "defeat") then


>**Theodore Exanthem says:** Sweet father of rot, alright already! Stop hitting me and tell me what you want me to do!


**Stop timer** named *defeat*


**Theodore Exanthem** clears hate list.


**Signaled to:**  [an interrogator](/npc/14050)
end

## Turn-Ins

local xloc = e.self:GetX();

local yloc = e.self:GetY();




if( **You turn in:** [Confession Document](/item/2344) and (xloc == -3098 and yloc == - [Fanged Talisman](/item/5872))) then 


>*Theodore Exanthem makes a big X at the bottom of the document and hands it back saying, 'A bunch of worthless thugs is all you folks are!'*


 **You receive:**  [Theodore's Confession](/item/2395) 


**Signaled to:**  [an interrogator](/npc/14050)


**Theodore Exanthem despawns.**

**This NPC *should* return incorrect items given.**
