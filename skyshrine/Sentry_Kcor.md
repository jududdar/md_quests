# Sentry Kcor
## Dialog

**You say:** `hail`



>**Sentry Kcor says:** Halt, who goes there? Hmmm. What manner of strangers are you? Let it be known that the Kin hold no love for outsiders, only those truly worthy may walk amongst the Kin.


if(**spawned NPC:**  [Sentry Enots](/npc/114566) and eq.get_entity_list():GetMobByNpcTypeID( [Sentry Enots](/npc/114566)):GetX() == -686 and eq.get_entity_list():GetMobByNpcTypeID( [Sentry Enots](/npc/114566)):GetY() == 50) then



eq.get_entity_list():GetMobByNpcTypeID( [Sentry Enots](/npc/114566)):Say("It was because of an outsider that the dragons were forced to flee. Outsiders must not be trusted.");



>**Sentry Kcor says:** Perhaps, but then again these strangers may be worthy of our trust unlike that vile Kragen Morshire, perhaps we should give them a chance to prove themselves truly worthy to walk amongst the Kin.



eq.get_entity_list():GetMobByNpcTypeID( [Sentry Enots](/npc/114566)):Say("Perhaps you are right Kcor, but we will see. ");


**You say:** `worthy`



>**Sentry Kcor says:** The vile giants, their hearts colder than the ice of Velious, wish to slay our kind and take the land for their own.  Their warriors wear helms of the finest steel, should you slay these warriors, return their helms and your worth to the Kin shall grow.


if(**spawned NPC:**  [Sentry Enots](/npc/114566) and eq.get_entity_list():GetMobByNpcTypeID( [Sentry Enots](/npc/114566)):GetX() == -686 and eq.get_entity_list():GetMobByNpcTypeID( [Sentry Enots](/npc/114566)):GetY() == 50) then



eq.get_entity_list():GetMobByNpcTypeID( [Sentry Enots](/npc/114566)):Say("I must speak with the Herald, Kcor please see to the gate until I return.");



eq.get_entity_list():GetMobByNpcTypeID( [Sentry Enots](/npc/114566)):CastToNPC():AssignWaypoints(1);



>**Sentry Kcor says:** Very well, Enots, but do not be long. Lord Yelinak would have your hide should invaders arrive while you are not at your post.

end

## Turn-Ins



local helmet =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_747.png" alt="" /> <a
                                href="/item/29062" data-url="29062" class="tooltip-link link">Giant Warrior Helmet</a>}

local storm_toe =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/29124" data-url="29124" class="tooltip-link link">Storm Giant Toes</a>}

local assignment =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_652.png" alt="" /> <a
                                href="/item/29624" data-url="29624" class="tooltip-link link">Mercenary Assignments</a>}

local frost_toe =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/29125" data-url="29125" class="tooltip-link link">Frost Giant Toes</a>}



if(helmet > 0) then





repeat



>**Sentry Kcor says:** Very good, you are on your way to proving yourself.



Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+15</span>)




Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+3</span>)




Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-7</span>)




 &#127873; **You receive:** 0 (+10000 exp)

 



helmet = helmet - 1;


until helmet == 0;

elseif(storm_toe > 0) then





repeat



>**Sentry Kcor says:** Ahh these will go nicely with the rest of my collection.  Here is a small reward for your trouble.



Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+10</span>)




Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+2</span>)




Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-5</span>)




 &#127873; **You receive:** 0 (+10000 exp)

**You receive coin:** 1-10 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 



storm_toe = storm_toe - 1;


until storm_toe == 0;

elseif(assignment > 0) then



repeat



>**Sentry Kcor says:** Ahhh yes! Well done " .. e.other:Race() .. ". Here is your reward. Your status with our people grows with each interloper you eradicate.



Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+5</span>)




Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+1</span>)




Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-2</span>)




 &#127873; **You receive:** 0 (+5000 exp)

**You receive coin:** 1-5 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 



assignment = assignment - 1;


until assignment == 0;

elseif(frost_toe > 0) then



repeat



>**Sentry Kcor says:** Ahh these will go nicely with the rest of my collection.  Here is a small reward for your trouble.



Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+5</span>)




Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+1</span>)




Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-2</span>)




 &#127873; **You receive:** 0 (+5000 exp)

**You receive coin:** 1-5 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 



frost_toe = frost_toe - 1;


until frost_toe == 0;



**This NPC *should* return incorrect items given.**
