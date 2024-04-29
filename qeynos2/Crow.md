# Crow
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then






>**Crow says:** Welcome to Crow's! If you're thirsty, we have a fine selection of brews and ales.


else



>**Crow says:** Heh...  With all you've done, I'm surprised you're still alive.





**You say:** `brew`



if **Faction** >= Indifferent then



>**Crow says:** It's my own personal recipe, and it's the best ale this side of the Serpent's Spine. Been having trouble keeping up with the demand for it, though. Especially with those little Irontoe drunkards running around.




else



>**Crow says:** Heh...  With all you've done, I'm surprised you're still alive.


**You say:** `kane`



>**Crow says:** Yeah, I need someone to run over to Kane's for me. I need to find out how many cases of [Crow's special brew] he needs for next week.

## Turn-Ins






if( **You turn in:** [A Tattered Leather Pouch](/item/17600)) then


>**Crow says:** What are you? The Rat's new bag man? Peh, he is useless. That bum drinks any gold he gets. Here ya go, kid!





* __Faction:__ [Circle of Unseen Hands](/faction/223) (2)


* __Faction:__ [Merchants of Qeynos](/faction/291) (-1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Kane Bayle](/faction/273) (1)


 **You receive:**  [Crow's Special Brew](/item/13901) (+250 exp)



**This NPC *should* return incorrect items given.**



## Signals


if(e.signal == 1) then


>**Crow says:** You ok Sabs?


**Signaled to:**  [Sabnie Blagard](/npc/2083)

elseif(e.signal == 2) then


>**Crow says:** 'Testing one two three four'


**Signaled to:**  [Sabnie Blagard](/npc/2083)

elseif(e.signal == 3) then


>**Crow says:** Excellent. To think that he thought he could stroll in here from Highpass and take over my action. He will learn the hard way what happens to merchants who think they can operate here without our support and protection.



local sabs = eq.get_entity_list():GetMobByNpcTypeID( [Sabnie Blagard](/npc/2083));




if ( sabs.valid ) then



e.self:FaceTarget(sabs);



elseif(e.signal == 4) then


>**Crow says:** Anything you say, my love.

elseif(e.signal == 5) then


>**Crow says:** Bwah! Ha! Ha! I love it when he does that! HA HA HA! You are too much, Flynn!
