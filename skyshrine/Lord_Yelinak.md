# Lord Yelinak
## Dialog

**You say:** `hail`



if **Faction** >= Amiable +100 then



>**Lord Yelinak says:** Welcome, young mortal. Word of your deeds has preceded your arrival. Your intentions seem honorable, young one, however my trust is not an easy thing to win these days. Like you, there has been another that came before me with the trust of the dragon kin, and trust them too I did, but alas that proved to be destructive. I note your deeds to this shrine young one, but should you wish my counsel, you must prove your worth beyond doubt. Perhaps a small challenge shall be of interest to you?


else



>**Lord Yelinak says:** I have nothing to speak about to the likes of you.


**You say:** `prove`



if **Faction** >= Amiable +100 then



>**Lord Yelinak says:** Then as agreed, young mortal, I will grant you one chance to prove your worth in my eyes. The Storm King Tormax sits on a throne carved from the skull of one of our fallen within the city of Kael, which disgraces the mighty children of Veeshan. His life alone is a blight upon the children of Veeshan. Should you be a true patriot to our cause, I seek of you but one task. Should you succeed in this task, not only will your actions offset the balance of this war in our favor, but will surely take a step in driving the vileness of the giants from our noble lands. Bring me, young one, the head of Tormax, and then we shall speak further.


else



>**Lord Yelinak says:** I have nothing to speak about to the likes of you.


**You say:** `treasure`



if **Faction** >= Amiable +100 then



>**Lord Yelinak says:** This sword is a symbol of our evolution and ancient heritage. Back when our feathered relatives were not so distant, a sword was forged and enchanted with the spirit of an elder griffin. This noble griffin bound his soul to the sword, the essence of his being honing the blade to an edge imperceptible to mortal eyes. Although our races have evolved away from each other, we still hold them in high regard. But if you think you are not worthy to wield this honor, return the sword to me and I have other tokens you may find of more use.


else



>**Lord Yelinak says:** I have nothing to speak about to the likes of you.

end

## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_980.png" alt="" /> <a
                                href="/item/30516" data-url="30516" class="tooltip-link link">King Tormax's Head</a>) then


if **Faction** >= Amiable +100 then



>*Lord Yelinak watches as you drop the colossal head of King Tormax to the ground before him. You sense intense hatred within Yelinak as he stares down at the bloody remains of a descendent of the one who slew his mate. Obviously the death of Tormax has done little to console the ancient snow dragon. Finally Yelinak speaks, 'I look upon this face, and even though he is dead, the hatred burns on. My grief and anger are unchanged even in the face of ultimate fate. His grandfather's act was so despicable and all-encompassing that it instilled an. immortal loathing. Nevertheless, you have completed the task I set before you and, as such, you deserve my gratitude. Please accept this [treasure].*



Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+50</span>)



Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+25</span>)



Your faction standing with [King Tormax](/faction/429) got worse (<span class='text-danger'>-25</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1211.png" alt="" /> <a
                                href="/item/29647" data-url="29647" class="tooltip-link link">Clawed Griffin Sword</a> (+1000 exp)

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1211.png" alt="" /> <a
                                href="/item/29647" data-url="29647" class="tooltip-link link">Clawed Griffin Sword</a>) then


if **Faction** >= Amiable +100 then



>**Lord Yelinak says:** I lost the scales that made these boots in a battle with Tormaxs minions. The casters of the shrine gathered these fallen scales up and fashioned a very powerful enchantment into these boots.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/29645" data-url="29645" class="tooltip-link link">White Dragonscale Boots</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/29645" data-url="29645" class="tooltip-link link">White Dragonscale Boots</a>) then


if **Faction** >= Amiable +100 then



>**Lord Yelinak says:** This helm was created by our smiths and enchanted by the priests of the shrine to provide protection to our new allies who have found that their heads are much more fragile than those of our kin.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_625.png" alt="" /> <a
                                href="/item/29648" data-url="29648" class="tooltip-link link">White Dragon Helm</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_625.png" alt="" /> <a
                                href="/item/29648" data-url="29648" class="tooltip-link link">White Dragon Helm</a>) then


if **Faction** >= Amiable +100 then



>**Lord Yelinak says:** This sword is a symbol of our evolution and ancient heritage. Back when our feathered relatives were not so distant, a sword was forged and enchanted with the spirit of an elder griffin. This noble griffin bound his soul to the sword, the essence of his being honing the blade to an edge imperceptible to mortal eyes. Although our races have evolved away from each other, we still hold them in high regard. But if you think you are not worthy to wield this honor, return the sword to me and I have other tokens you may find of more use.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1211.png" alt="" /> <a
                                href="/item/29647" data-url="29647" class="tooltip-link link">Clawed Griffin Sword</a> 

 


**This NPC *should* return incorrect items given.**
