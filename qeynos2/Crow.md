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






if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/17600" data-url="17600" class="tooltip-link link">A Tattered Leather Pouch</a>) then


>**Crow says:** What are you? The Rat's new bag man? Peh, he is useless. That bum drinks any gold he gets. Here ya go, kid!





Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+2</span>)


Your faction standing with [Merchants of Qeynos](/faction/291) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Corrupt Qeynos Guards](/faction/230) got better (<span class='text-success'>+1</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Kane Bayle](/faction/273) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_586.png" alt="" /> <a
                                href="/item/13901" data-url="13901" class="tooltip-link link">Crow's Special Brew</a> (+250 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-8 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 



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
