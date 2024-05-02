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


eq.move_to(-3098,- <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/5872" data-url="5872" class="tooltip-link link">Fanged Talisman</a>,94,160,true);




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




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/2344" data-url="2344" class="tooltip-link link">Confession Document</a> and (xloc == -3098 and yloc == - <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/5872" data-url="5872" class="tooltip-link link">Fanged Talisman</a>)) then 


>*Theodore Exanthem makes a big X at the bottom of the document and hands it back saying, 'A bunch of worthless thugs is all you folks are!'*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/2395" data-url="2395" class="tooltip-link link">Theodore's Confession</a> 

 


**Signaled to:**  [an interrogator](/npc/14050)


**Theodore Exanthem despawns.**

**This NPC *should* return incorrect items given.**
