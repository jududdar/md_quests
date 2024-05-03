# Palon Deskeb


## Dialog

**You say:** `hail`



e.self:Say(string.format("Pleased to meet you. %s. Have you seen how clear the water is underneath the Academy? All sorts of life could flourish there. What a shame there are no [Marr Minnows] there.",e.other:GetName()));

**You say:** `marr minnow`



>**Palon Deskeb says:** The Marr Minnow swims in the pond near the Temple of Marr. I wish I had one. Not a dead one. A live one. I need someone to [get the minnow].

**You say:** `get the minnow`



if **Faction** >= Amiable then



>**Palon Deskeb says:** Please try. Here you are. Take this jar. Offer the jar to the minnows. Maybe they will swim into it.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1006.png" alt="" /> <a
                                href="/item/13861" data-url="13861" class="tooltip-link link">A Jar of Liquid</a>


elseif **Faction** >= Indifferent then



>**Palon Deskeb says:** The word of mouth in the Academy of Arcane Science is that you are no foe, but you have yet to prove your worth to us. Perform more tasks for the great Tara Neklene.


else



>**Palon Deskeb says:** You had best leave my sight. I am a faithful member of the Academy of Arcane Science and you are no ally of ours.

end



## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1018.png" alt="" /> <a
                                href="/item/13862" data-url="13862" class="tooltip-link link">Fish in a Jar</a>) then


>**Palon Deskeb says:** Oh! A beautiful Marr Minnow. This shall look grand in my aquarium! How lucky that you are a friend to the Academy of Arcane Science. Take your reward.


Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+5</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+1</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_547.png" alt="" /> <a
                                href="/item/13002" data-url="13002" class="tooltip-link link">Torch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13007" data-url="13007" class="tooltip-link link">Ration</a>) (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-2 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


