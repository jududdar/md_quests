# Baxok Curhunter



[Baxok Curhunter](/npc/55136) is a level 61 Gnome GM Warrior that spawns in [Ak'Anon](/zone/55).





## Dialog

**You say:** `hail`



>**Baxok Curhunter says:** Hail, Soandso. I invite you to serve the mighty state of Ak'Anon by becoming a Gemchopper. We gnomes are not known for our warrior skills, but those few who endure and survive to become elite amongst our warriors soon find that the technology of the gnomes has found its way into our halls. You must be a [new recruit] or [an outsider], perhaps?

**You say:** `new recruit`



if **Faction** >= Amiable then



>**Baxok Curhunter says:** Well, good to make your acquaintance, Soandso. Maybe someday you shall be a great Watchman. Until then, I have a task for you. Will you [serve the Crown] or has a yellow streak appeared upon your back?


elseif( **Faction is** == Indifferent) then



>**Baxok Curhunter says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Baxok Curhunter says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `an outsider`



>**Baxok Curhunter says:** I should have guessed as much. You look the part.

**You say:** `serve the crown`



if(**Your level** <=5 ) then



>**Baxok Curhunter says:** You are too inexperienced. Leave that business to someone more worldly.


else



>**Baxok Curhunter says:** Go to the Lesser Faydarks. There you will seek out a fairy city. It seems the little pests have stolen one of our fabulous clockworks. Destroy the clockwork and bring me proof. Be very careful. The fairy folk may be small, but they pack a punch.


**You say:** `meldrath`



>**Baxok Curhunter says:** Meldrath is the mad gnome.  He used to be a member of the Eldritch Collective.  Some say he lost his mind while he was working on a formula he obtained from other worlds.  He used to lead the cult called the [Asylum of the Mad].

**You say:** `asylum`



>**Baxok Curhunter says:** The Asylum of the Mad was formed by the mad gnome, Meldrath. Under his direction, they were trying to build some giant mechanical titan.  We recently sent all of our clockworks into the Steamfont Mountains to destroy their evil cult.
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18770" data-url="18770" class="tooltip-link link">Recruitment Summons</a>) then 


>**Baxok Curhunter says:** I, Baxok, guildmaster, welcome you to Gemchopper Hall, young warrior! You are expected to serve his majesty, King Ak'Anon, with pride. You have much to learn. You may report to any of the trainers for further guidance. Go forth and serve!


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+100</span>)


Your faction standing with [Merchants of Ak`Anon](/faction/288) got better (<span class='text-success'>+25</span>)


Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+25</span>)


Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-25</span>)


Your faction standing with [Clan Grikbar](/faction/1604) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13520" data-url="13520" class="tooltip-link link">Torn and Ripped Tunic*</a> (+20 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/13344" data-url="13344" class="tooltip-link link">Blackbox XIVD</a>) then 


>**Baxok Curhunter says:** I can hardly believe you destroyed the clockwork. The last ten men I sent became fairy fodder. Thank you. Here is a token of my appreciation. Serve Ak'Anon well and we shall treat you well.





Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+20</span>)


Your faction standing with [Merchants of Ak`Anon](/faction/288) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+5</span>)


Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Clan Grikbar](/faction/1604) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_542.png" alt="" /> <a
                                href="/item/9002" data-url="9002" class="tooltip-link link">Round Shield</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/1001" data-url="1001" class="tooltip-link link">Cloth Cap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/1002" data-url="1002" class="tooltip-link link">Cloth Veil</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_500.png" alt="" /> <a
                                href="/item/1003" data-url="1003" class="tooltip-link link">Cloth Choker</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/1004" data-url="1004" class="tooltip-link link">Cloth Shirt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/1005" data-url="1005" class="tooltip-link link">Cloth Shawl</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_656.png" alt="" /> <a
                                href="/item/1006" data-url="1006" class="tooltip-link link">Cloth Cape</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_572.png" alt="" /> <a
                                href="/item/1007" data-url="1007" class="tooltip-link link">Cloth Cord</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_670.png" alt="" /> <a
                                href="/item/1008" data-url="1008" class="tooltip-link link">Cloth Sleeves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_638.png" alt="" /> <a
                                href="/item/1009" data-url="1009" class="tooltip-link link">Cloth Wristband</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_517.png" alt="" /> <a
                                href="/item/1010" data-url="1010" class="tooltip-link link">Cloth Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_517.png" alt="" /> <a
                                href="/item/1010" data-url="1010" class="tooltip-link link">Cloth Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_631.png" alt="" /> <a
                                href="/item/1011" data-url="1011" class="tooltip-link link">Cloth Pants</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
