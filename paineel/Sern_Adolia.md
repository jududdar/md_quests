# Sern Adolia



[Sern Adolia](/npc/75072) is a level 61 Erudite GM Cleric that spawns in [Paineel](/zone/75).



## Dialog

**You say:** `hail`



>**Sern Adolia says:** I hope you have a good reason for disturbing my contemplations. Perhaps you [seek the knowledge] of those who meditate within this Temple of Fear?

**You say:** `seek.* knowledge`



>**Sern Adolia says:** It is the secrets of Fear you seek, but first you must prove your devotion to our temple. There are pack rats within the city that have a habit of getting into things. Some of these rats have ingested a concoction developed by the necromancers of this great city. The rats have since died and, due to the concoction, their undead corpses now roam the fields. Bring me four livers from these undead rats so that we may examine them.

**You say:** `duties`



if **Faction** >= Amiable then



>**Sern Adolia says:** The primary duty of this temple is to spread terror, fright, and dread as a symbol of your devotion to our lord Cazic Thule. We are currently researching a means of summoning avatars of Fright, Terror and Dread, the primary minions of the Faceless in his home plane. Will you [assist me in summoning] the avatar of Fright?


elseif **Faction** >= Indifferent then



>**Sern Adolia says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.




else



>**Sern Adolia says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!


**You say:** `assist`



if **Faction** >= Amiable then



>**Sern Adolia says:** In order to summon the avatar of Fright. I require some special components for the ritual. Fetch me the flesh of a zombie. the dust used in the process of mummification. [charred bone chips]. and a [vial of Tunare's Breath].


elseif **Faction** >= Indifferent then



>**Sern Adolia says:** I sense the potential to learn the ways of fear within you. Continue striving to master your fear and one day perhaps you can be of service to our Lord Cazic-Thule.


else



>**Sern Adolia says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!


**You say:** `chips`



>**Sern Adolia says:** Some time ago a necromancer by the name of Obretl was sent to slay Rathmana Allin and his abomination of an adopted son. Ortallius. Obretl failed in his task and now haunts a small ruin in the desert of Ro cursed by Solusek to wallow in his failure in the form of a burning skeleton. Slay Obretl to free him from his pathetic existence and gather his charred remains.

**You say:** `vial`



>**Sern Adolia says:** Tunare's Breath is a life-giving potion created by the Fier'Dal Soldiers of Tunare. Seek out the druid Kalayia who is known to wander the Faydarks in search of reagents for potions. Procure from her a vial of Tunare's Breath. Shed her blood if need be.
end



## Turn-Ins



local text = "I need no fewer than four infected rat livers!! Now, go get me what I require!!";

local text1 = "I require all four reagents, anything less is useless. Incompetence will get you nowhere amongst the faithful of Cazic-Thule!";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/18019" data-url="18019" class="tooltip-link link">Harbingers of Fear Guild Note</a>) then 


>**Sern Adolia says:** You are welcomed into the fold. Now go out. and prove yourself. young one. You have much to learn about the Dark Truth.


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+100</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-100</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-100</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-100</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-100</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13573" data-url="13573" class="tooltip-link link">Blood Splattered Tunic</a> (+20 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/13270" data-url="13270" class="tooltip-link link">Infected Rat Livers</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/13270" data-url="13270" class="tooltip-link link">Infected Rat Livers</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/13270" data-url="13270" class="tooltip-link link">Infected Rat Livers</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/13270" data-url="13270" class="tooltip-link link">Infected Rat Livers</a>) then


>**Sern Adolia says:** Well done, go now and continue your contemplations of fear. Keep up with your [duties] and you will soon be reaping the rewards granted by our Lord Cazic-Thule!!


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+5</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_566.png" alt="" /> <a
                                href="/item/1437" data-url="1437" class="tooltip-link link">Initiate Symbol of Cazic Thule</a> (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13074" data-url="13074" class="tooltip-link link">Zombie Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/16990" data-url="16990" class="tooltip-link link">Embalming Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/14102" data-url="14102" class="tooltip-link link">Charred Bone Chips</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_599.png" alt="" /> <a
                                href="/item/14103" data-url="14103" class="tooltip-link link">Vial of Tunares Breath</a>) then


>**Sern Adolia says:** Excellent Job Soandso. These components will help with our research immeasurably. You will soon be reaping the rewards granted by our Lord Cazic-Thule!! If you want to further assist our research effots, talk to Atdehim Sqonci.


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+30</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-30</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-30</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-30</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-30</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_628.png" alt="" /> <a
                                href="/item/14100" data-url="14100" class="tooltip-link link">Fright Forged Helm</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**






