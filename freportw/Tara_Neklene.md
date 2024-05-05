# Tara Neklene



[Tara Neklene](/npc/9077) is a level 61 Human GM Magician that spawns in [West Freeport](/zone/9).



## Dialog

**You say:** `hail`



>**Tara Neklene says:** It is always a pleasure to meet a new face. We have many who travel far and wide to visit our great academy. Many who brave the long trip by boat. Many who dare to cross the territory of the [Deathfist orcs].

**You say:** `deathfist orcs`



>**Tara Neklene says:** The Deathfist are a clan of orcs. They are not very powerful, yet I hear they dabble in the circles of magic. Their skills in the ways of magic are limited. It is my duty to study them. I shall pay for your services. Will you [assist with the research]?

**You say:** `assist with the research`



>**Tara Neklene says:** Yes. You will do. Go into the lands which surround Freeport. There you shall encounter Deathfist apprentices. They are as young as yourself and each should carry an orc cantrip. Return one for further studies. Do so and you will earn your pay as well as our respect.

**You say:** `test the might of the orc oracles`



if **Faction** >= Amiable +100 then



>**Tara Neklene says:** You have heightened your knowledge to the appropriate rank. You are ready to challenge the Deathfist oracles. Do so and return one oracle scroll which any of them may have. If I am in a good mood when you return, you shall soon be summoning elementals.


elseif **Faction** >= Indifferent then



>**Tara Neklene says:** The word of mouth in the Academy of Arcane Science is that you are no foe, but you have yet to prove your worth to us. Perform more tasks for the great Tara Neklene.


else



>**Tara Neklene says:** You had best leave my sight. I am a faithful member of the Academy of Arcane Science and you are no ally of ours.

end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13845" data-url="13845" class="tooltip-link link">Illegible Cantrip</a>) then


>**Tara Neklene says:** Very fine work, my young apprentice. This shall be very useful in understanding their ways. I have heard rumors of a scribe who can decipher these scrolls. He is said to frequent the local taverns. Bah!! If I cannot decipher them, no one can!! Continue with your work. Soon you shall advance enough to [test the might of the orc oracles].


Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+10</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+2</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13005" data-url="13005" class="tooltip-link link">Iron Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_570.png" alt="" /> <a
                                href="/item/13007" data-url="13007" class="tooltip-link link">Ration</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_547.png" alt="" /> <a
                                href="/item/13002" data-url="13002" class="tooltip-link link">Torch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13006" data-url="13006" class="tooltip-link link">Water Flask</a>) (+250 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_863.png" alt="" /> <a
                                href="/item/13225" data-url="13225" class="tooltip-link link">Illegible Scroll</a>) then


>**Tara Neklene says:** Wonderful! You have survived the might of an oracle. With this we can now continue our experiments. Now you may continue your teaching and study the power to summon those of earth, air, water and fire.


Your faction standing with [Arcane Scientists](/faction/220) got better (<span class='text-success'>+15</span>)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+3</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got worse (<span class='text-danger'>-2</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15317" data-url="15317" class="tooltip-link link">Spell: Elementalkin: Air</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15058" data-url="15058" class="tooltip-link link">Spell: Elementalkin: Earth</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15316" data-url="15316" class="tooltip-link link">Spell: Elementalkin: Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15315" data-url="15315" class="tooltip-link link">Spell: Elementalkin: Water</a>) (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-2 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-15 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**

