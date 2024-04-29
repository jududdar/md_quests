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



local helmet =  **You turn in:**  { [Giant Warrior Helmet](/item/29062)}

local storm_toe =  **You turn in:**  { [Storm Giant Toes](/item/29124)}

local assignment =  **You turn in:**  { [Mercenary Assignments](/item/29624)}

local frost_toe =  **You turn in:**  { [Frost Giant Toes](/item/29125)}



if(helmet > 0) then





repeat



>**Sentry Kcor says:** Very good, you are on your way to proving yourself.



* __Faction:__ [Claws of Veeshan](/faction/430) (15)




* __Faction:__ [Yelinak](/faction/436) (3)




* __Faction:__ [Kromzek](/faction/448) (-7)




 **You receive:** 0 (+10000 exp)



helmet = helmet - 1;


until helmet == 0;

elseif(storm_toe > 0) then





repeat



>**Sentry Kcor says:** Ahh these will go nicely with the rest of my collection.  Here is a small reward for your trouble.



* __Faction:__ [Claws of Veeshan](/faction/430) (10)




* __Faction:__ [Yelinak](/faction/436) (2)




* __Faction:__ [Kromzek](/faction/448) (-5)




 **You receive:** 0 (+10000 exp)



storm_toe = storm_toe - 1;


until storm_toe == 0;

elseif(assignment > 0) then



repeat



>**Sentry Kcor says:** Ahhh yes! Well done " .. e.other:Race() .. ". Here is your reward. Your status with our people grows with each interloper you eradicate.



* __Faction:__ [Claws of Veeshan](/faction/430) (5)




* __Faction:__ [Yelinak](/faction/436) (1)




* __Faction:__ [Kromzek](/faction/448) (-2)




 **You receive:** 0 (+5000 exp)



assignment = assignment - 1;


until assignment == 0;

elseif(frost_toe > 0) then



repeat



>**Sentry Kcor says:** Ahh these will go nicely with the rest of my collection.  Here is a small reward for your trouble.



* __Faction:__ [Claws of Veeshan](/faction/430) (5)




* __Faction:__ [Yelinak](/faction/436) (1)




* __Faction:__ [Kromzek](/faction/448) (-2)




 **You receive:** 0 (+5000 exp)



frost_toe = frost_toe - 1;


until frost_toe == 0;



**This NPC *should* return incorrect items given.**
