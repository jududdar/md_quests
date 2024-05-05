# Jarah Reskan



[Jarah Reskan](/npc/55135) is a level 61 Gnome GM Warrior that spawns in [Ak'Anon](/zone/55).





## Dialog

**You say:** `hail`



>**Jarah Reskan says:** Greetings, child. Welcome to Gemchopper Hall. I trust that you are a [warrior], or perhaps you are lost..?

**You say:** `lost`



>**Jarah Reskan says:** One can easily get lost in Ak'Anon. You must get your vision checked. If you are truly lost, I would advise speaking with a mechanical guide. There should be one close by on the main walkway.

**You say:** `warrior`



if **Faction** >= Amiable then 



>**Jarah Reskan says:** That is good news! We gnomes are not known for our love of battle so it is always good to bring new blood into our ranks. We shall prove our worth as warriors to all other races. For now. there is much to do in Ak'Anon. There are [rogue clockworks] and the [cargo clockwork].


elseif( **Faction is** == Indifferent) then



>**Jarah Reskan says:** You must show a greater allegiance to the Gemchoppers before we can speak with you.  Search the hills for rogue clockworks.  Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.


else



>**Jarah Reskan says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `rogue clockworks`



>**Jarah Reskan says:** The clockworks are the responsibility of Manik Compolten. Speak with him - I am sure he is here somewhere.

**You say:** `cargo clockwork`



>**Jarah Reskan says:** The cargo clockwork is located near the entrance to Ak'Anon in the Steamfont Mountains. It runs a delivery to the windmills every five days at eight in the morning. There have been attacks by a group of highwaymen. They are quite a formidable group. I have offered a reward for their heads. Be very careful if you plan on escorting the cargo clockwork. This trio of bandits is very strong.

**You say:** `blackbox`



>**Jarah Reskan says:** If you have a clockwork blackbox which is still intact, take it to [Manik Compolten].  All clockwork matters go through him.

**You say:** `manik compolten`



if **Faction** >= Indifferent then 



>**Jarah Reskan says:** Manik is a trainer within this guild. The clockworks are his responsibility. Speak with him - I am sure he is here somewhere.


else



>**Jarah Reskan says:** You are lucky I do not cut you in half right where you stand. Your actions so far have proven you an enemy to the Gemchoppers. Leave while you still can!


**You say:** `meldrath`



>**Jarah Reskan says:** Meldrath is the mad gnome.  He used to be a member of the Eldritch Collective.  Some say he lost his mind while he was working on a formula he obtained from other worlds.  He used to lead the cult called the [Asylum of the Mad].

**You say:** `asylum`



>**Jarah Reskan says:** The Asylum of the Mad was formed by the mad gnome, Meldrath. Under his direction, they were trying to build some giant mechanical titan.  We recently sent all of our clockworks into the Steamfont Mountains to destroy their evil cult.
end



## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/1270" data-url="1270" class="tooltip-link link">Hector's Severed Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/1319" data-url="1319" class="tooltip-link link">Jerald's Severed Head</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_982.png" alt="" /> <a
                                href="/item/1323" data-url="1323" class="tooltip-link link">Renaldo's Severed Head</a>) then


>**Jarah Reskan says:** I heard our shipment made it back safely. These heads will send a message to any other thief that plans on robbing our cargo shipments. Thank you Soandso, take this coin as your reward. I’m sorry to say we’re currently out of masks.


Your faction standing with [Gem Choppers](/faction/255) got better (<span class='text-success'>+2</span>)


Your faction standing with [Merchants of Ak`Anon](/faction/288) got better (<span class='text-success'>+1</span>)


Your faction standing with [King Ak`Anon](/faction/333) got better (<span class='text-success'>+1</span>)


Your faction standing with [Dark Reflection](/faction/238) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Clan Grikbar](/faction/1604) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** 0 (+1500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-9 <img src='/static/icons/item_647.png' width='14' height='14'/> 


**This NPC *should* return incorrect items given.**
