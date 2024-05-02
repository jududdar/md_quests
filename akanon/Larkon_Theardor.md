# Larkon Theardor
## Dialog

**You say:** `hail`



>**Larkon Theardor says:** Greetings! Welcome to the Library of Mechanimagica. You must be a [current member of the Library] or has my [mind begun to slip]?

**You say:** `slip`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** What!!? That was but a joke. I try to make you feel comfortable with a little levity and you proclaim my mind has gone the way of Meldrath's. Well.. enough frivolity. You will do your part to help in the menial tasks of the Collective. Do you want the [clean tasks] or the [dirty tasks]?


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `tasks`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** Clean.. Dirty.. It matters not. You have upset me with your rude remarks. You will go to the Steamfont Mountains. There you will find Fodin and tell him I have sent you. He will have a nice tidy task for you. A bath!! Be on your way!


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `current member of the library`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** Good. The last thing a member of the Eldritch Collective needs is to lose his mind. Look what happened to Meldrath. Enough chitchat. I am Larkon and it is not my job to teach you. It is my job to direct you to service. We require items and such to complete our studies. We need someone of moderate skill to [gather minotaur horns] and [collect basilisk tongues].


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `gather minotaur horns`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** We magicians require the horns of minotaurs. We crush them down and use the powder in many of our tests. Go and fetch two minotaur horns. Do not return empty-handed. I await your return as does your reward.


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `basilisk tongues`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** Very good of you. Go beyond the land of the gnomes and seek out basilisks. Return four of their tongues to me and I shall share the knowledge of the magicians of the Eldritch Collective.


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.


**You say:** `kaladim`



if **Faction** >= Amiable then 



>**Larkon Theardor says:** We need someone to venture to the dwarven kingdom of Kaladim and speak with Myre of Miner's Guild 628. She has a delivery of special pestles made from bozinite. If you feel up to it, go to her and tell her you are from the Eldritch Collective and desire the bozinite pestles. Return them to me.


elseif( **Faction is** == Indifferent) then



>**Larkon Theardor says:** There is much more you must do for the Library of Mechanimagica before such things can be revealed to you.  Perhaps fetching minotaur horns and returning them to Professor Theardor will earn you membership to the Library of Mechanimagica.


else



>**Larkon Theardor says:** You dare to speak to a member of the Eldritch Collective! You had best leave before you find your soul displaced from your body.

end

## Turn-Ins



local text = "I will require two minotaur horns for further studies.";

local text1 = "I believe I called for FOUR basilisk tongues.";



if **Faction** >= Apprehensive and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_807.png" alt="" /> <a
                                href="/item/13077" data-url="13077" class="tooltip-link link">Minotaur Horn</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_807.png" alt="" /> <a
                                href="/item/13077" data-url="13077" class="tooltip-link link">Minotaur Horn</a>) then 


>**Larkon Theardor says:** Fine work. You have earned the respect of the Library. Here is a small token of our appreciation. We shall have this ground down as soon as we find someone to go to Kaladim.


Your faction standing with [Eldritch Collective](/faction/245) got better (<span class='text-success'>+20</span>)



Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-3</span>)



Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+3</span>)



Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** 0 (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13271" data-url="13271" class="tooltip-link link">Air Tight Box</a>) then 


>**Larkon Theardor says:** Whew! What smells of rotting disease? Oh... It's you. I see you've gathered all the diseased livers. I shall have them incinerated in the scrapyard. The only reason we do this is to keep the Dark Reflection from using these components in their black arts. Take this. I hope you use it wisely. Oh, and... take a bath. You stink!


Your faction standing with [Eldritch Collective](/faction/245) got better (<span class='text-success'>+10</span>)



Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+1</span>)



Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_946.png" alt="" /> <a
                                href="/item/10017" data-url="10017" class="tooltip-link link">Turquoise</a> (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1087.png" alt="" /> <a
                                href="/item/12160" data-url="12160" class="tooltip-link link">Basilisk Tongue</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1087.png" alt="" /> <a
                                href="/item/12160" data-url="12160" class="tooltip-link link">Basilisk Tongue</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1087.png" alt="" /> <a
                                href="/item/12160" data-url="12160" class="tooltip-link link">Basilisk Tongue</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1087.png" alt="" /> <a
                                href="/item/12160" data-url="12160" class="tooltip-link link">Basilisk Tongue</a>) then 


>**Larkon Theardor says:** Very very good! I can use these in some of our experiments. These tongues are hard to come by and more than a few of our scouts have been turned to stone because of these creatures, but I'm sure you found that out by now, eh?


Your faction standing with [Eldritch Collective](/faction/245) got better (<span class='text-success'>+10</span>)



Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+1</span>)



Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15205" data-url="15205" class="tooltip-link link">Spell: True North</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15211" data-url="15211" class="tooltip-link link">Spell: Summon Drink</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15288" data-url="15288" class="tooltip-link link">Spell: Minor Shielding</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15310" data-url="15310" class="tooltip-link link">Spell: Flare</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15311" data-url="15311" class="tooltip-link link">Spell: Summon Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15313" data-url="15313" class="tooltip-link link">Spell: Fire Flux</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15331" data-url="15331" class="tooltip-link link">Spell: Reclaim Energy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15050" data-url="15050" class="tooltip-link link">Spell: Summon Food</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15093" data-url="15093" class="tooltip-link link">Spell: Burst of Flame</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15315" data-url="15315" class="tooltip-link link">Spell: Elementalkin: Water</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15316" data-url="15316" class="tooltip-link link">Spell: Elementalkin: Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15058" data-url="15058" class="tooltip-link link">Spell: Elementalkin: Earth</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15317" data-url="15317" class="tooltip-link link">Spell: Elementalkin: Air</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15318" data-url="15318" class="tooltip-link link">Spell: Summon Bandages</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15036" data-url="15036" class="tooltip-link link">Spell: Gate</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15094" data-url="15094" class="tooltip-link link">Spell: Burn</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15246" data-url="15246" class="tooltip-link link">Spell: Lesser Shielding</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15322" data-url="15322" class="tooltip-link link">Spell: Flame Bolt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15323" data-url="15323" class="tooltip-link link">Spell: Eye of Zomm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15325" data-url="15325" class="tooltip-link link">Spell: Dimensional Pocket</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15851" data-url="15851" class="tooltip-link link">Spell: Renew Elements</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15324" data-url="15324" class="tooltip-link link">Spell: Shock of Blades</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15332" data-url="15332" class="tooltip-link link">Spell: Shield of Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15400" data-url="15400" class="tooltip-link link">Spell: Elementaling: Air</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15399" data-url="15399" class="tooltip-link link">Spell: Elementaling: Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15398" data-url="15398" class="tooltip-link link">Spell: Elementaling: Water</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15042" data-url="15042" class="tooltip-link link">Spell: Invisibility</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15613" data-url="15613" class="tooltip-link link">Spell: Staff of Tracing</a>) (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_732.png" alt="" /> <a
                                href="/item/13272" data-url="13272" class="tooltip-link link">Bozinite Pestle</a>) then 


>**Larkon Theardor says:** The Eldritch Collective thanks you. You have done a great service. We need these special bozinite pestles for use with our eldritch mortars. Here is a scroll from our library. Study it and use it wisely.


Your faction standing with [Eldritch Collective](/faction/245) got better (<span class='text-success'>+10</span>)



Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)



Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+1</span>)



Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15400" data-url="15400" class="tooltip-link link">Spell: Elementaling: Air</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15399" data-url="15399" class="tooltip-link link">Spell: Elementaling: Fire</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15398" data-url="15398" class="tooltip-link link">Spell: Elementaling: Water</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15397" data-url="15397" class="tooltip-link link">Spell: Elementaling: Earth</a>) (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
