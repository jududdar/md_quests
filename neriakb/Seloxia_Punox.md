# Seloxia Punox



[Seloxia Punox](/npc/41066) is a level 61 Dark Elf GM Warrior that spawns in [Neriak - Commons](/zone/41).



## Dialog

**You say:** `hail`



>*Seloxia Punox 's eyes flare with fury as her beautiful features twist into a snarl of hatred that echoes her hissing voice, 'How dare you address me in such a fashion?!  I am the leader of the Indigo Brotherhood!!  You are lucky I do not strike you down where you stand!  You shall address me as 'Mistress.'  Many warriors have died so that I might gain this title.'*

**You say:** `mistress`



e.self:Emote("maintains her imposing posture as she indifferently eyes Soandso, 'You stand now in the Cauldron of Hate 

**You say:** `little test`



if **Faction** >= Amiable then



>**Seloxia Punox says:** My little test is this. I desire a report from Ambassador K'Rynn in the Ogre city of Oggok. You shall run to him. I will not wait until you raise your fighting skills. Combat is not your test. Overcoming the odds is. Fast agile warriors are we. We desire nothing less. Will you [venture to Oggok]?


elseif **Faction** >= Indifferent then



>**Seloxia Punox says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Seloxia Punox says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `venture to oggok`



if **Faction** >= Amiable then



>**Seloxia Punox says:** Then you will go at once. Find your own way. Deliver this note to Ambassador K'Rynn and he shall give you the note to return to me. Do not stop to practice your skills. I offer this test to only the young warriors. If you die, then so be it. We need not inferior warriors. Now go!!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18842" data-url="18842" class="tooltip-link link">A Sealed Letter</a>


elseif **Faction** >= Indifferent then



>**Seloxia Punox says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Seloxia Punox says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.



end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18751" data-url="18751" class="tooltip-link link">A tattered note</a>) then


>**Seloxia Punox says:** I shall reserve any official welcoming until you have proven yourself a suitable member for the Indigo Brotherhood. That proof shall be obtained by your progression in your training. See Yegek B'Larin, one of my most trusted trainers in the Brotherhood and obey his command carefully if you wish to succeed as a member of the Brotherhood.


Your faction standing with [Indigo Brotherhood](/faction/270) got better (<span class='text-success'>+100</span>)


Your faction standing with [Emerald Warriors](/faction/326) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Steel Warriors](/faction/311) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-200</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13580" data-url="13580" class="tooltip-link link">Old Training Tunic*</a> (+20 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_866.png" alt="" /> <a
                                href="/item/18843" data-url="18843" class="tooltip-link link">a sealed letter</a>) then   


>**Seloxia Punox says:** Very fine work my young warrior. You may soon be ready to become a Teir'Dal courier. For now we shall reward you. This will assist you in further service to the Indigo Brotherhood and King Naythox Thex.


Your faction standing with [Indigo Brotherhood](/faction/270) got better (<span class='text-success'>+10</span>)


Your faction standing with [Emerald Warriors](/faction/326) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Steel Warriors](/faction/311) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Primordial Malice](/faction/1522) got worse (<span class='text-danger'>-20</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_580.png" alt="" /> <a
                                href="/item/5026" data-url="5026" class="tooltip-link link">Bronze Short Sword</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/1001" data-url="1001" class="tooltip-link link">Cloth Cap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/1002" data-url="1002" class="tooltip-link link">Cloth Veil</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_500.png" alt="" /> <a
                                href="/item/1003" data-url="1003" class="tooltip-link link">Cloth Choker</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/1004" data-url="1004" class="tooltip-link link">Cloth Shirt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/1005" data-url="1005" class="tooltip-link link">Cloth Shawl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_569.png" alt="" /> <a
                                href="/item/5014" data-url="5014" class="tooltip-link link">Rusty Axe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_579.png" alt="" /> <a
                                href="/item/5015" data-url="5015" class="tooltip-link link">Rusty Scythe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5021" data-url="5021" class="tooltip-link link">Rusty Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/5027" data-url="5027" class="tooltip-link link">Bronze Long Sword</a>) (+250 exp)

 

**This NPC *should* return incorrect items given.**






