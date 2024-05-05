# Gardern



[Gardern](/npc/80034) is a level 36 High Elf Wizard that spawns in [Temple of Solusek Ro](/zone/80).






## Dialog

if **Faction** >= Indifferent then



**You say:** `Hail`




>**Gardern says:** I am Gardern, listed among the chosen of Solusek Ro.  I hold the lore to the [Staff of Temperate Flux] and the [Weeping Wand] - items coveted by my Wizardly brethren.


**You say:** `staff of temperate flux`




>**Gardern says:** The Staff of Temperate Flux is a boon to those who dabble in the elemental arts, for it can increase the susceptibility of a creature to both fire and cold.  Are you [interested in the staff]?


**You say:** `interested.* staff`




>**Gardern says:** I will craft you a Staff of Temperate Flux, but you must bring me the components which I require to make it.  I will need a Heart of Fire from an Inferno Goblin Wizard in the Caverns of Solusek, a Heart of Frost from a Goblin Wizard in the Caverns of Permafrost, a Rod of Bone from a Stone Skeleton by the shores of Lake Rathe and a Staff of Ro.  Bring me these items, and I will make you your staff.


**You say:** `weeping wand`




>**Gardern says:** The Weeping Wand is a fine item for a Wizard - it can aid as a focus for concentration, and, if needed, be used to parry as well.  Are you [interested in the wand]?


**You say:** `interested.* wand`




>**Gardern says:** I can make you a Weeping Wand, but you will need to bring me certain components.  I will need a Silver Wand from a Silvered Guard in the Temple Cazic Thule, A Bloodblack Wand from the Mountains of Rathe, Twice-Woven Silk from a Faerie Guard in Faydark and a Scepter of Sorrow from the Tomb in Castle Mistmoore.  Bring me these items and I will make for you a Weeping Wand.


else


**Gardern says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";



if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/10548" data-url="10548" class="tooltip-link link">Heart of Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/10549" data-url="10549" class="tooltip-link link">Heart of Frost</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_809.png" alt="" /> <a
                                href="/item/10550" data-url="10550" class="tooltip-link link">Rod of Bone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/6048" data-url="6048" class="tooltip-link link">Darkwood Staff</a>) then


>**Gardern says:** Well done, Soandso - here is the staff of Temperate Flux. Use it with the blessings of the Temple of Solusek Ro.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/6342" data-url="6342" class="tooltip-link link">Staff of Temperate Flux</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/10551" data-url="10551" class="tooltip-link link">Bloodblack Wand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/6338" data-url="6338" class="tooltip-link link">Silver Wand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_821.png" alt="" /> <a
                                href="/item/14364" data-url="14364" class="tooltip-link link">A Scepter</a>) then


>**Gardern says:** Well done, Soandso. Now I will craft your Weeping Wand, as promised.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/6341" data-url="6341" class="tooltip-link link">Weeping Wand</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10034" data-url="10034" class="tooltip-link link">Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10034" data-url="10034" class="tooltip-link link">Sapphire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10000" data-url="10000" class="tooltip-link link">Lambent Stone</a>) then


>**Gardern says:** Here is your prize - a lambent sapphire.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10119" data-url="10119" class="tooltip-link link">Lambent Sapphire</a> (+1000 exp)

 
end






