# Emissary Glib



[Emissary Glib](/npc/49127) is a level 20 Froglok Warrior that spawns in [Oggok](/zone/49).



## On NPC Spawn

**Set a timer** named *depop* for 300 seconds


## Dialog

**You say:** `hail`



>**Emissary Glib says:** Gloop.. Are you the one? Who sent you?

**You say:** `marda`



>**Emissary Glib says:** <Gloop>.. Good. I am the secret emissary of the frogloks of Guk. I have come to help your community, provided, that is, that you help mine. Gloop.. I want you to track down and kill the troll hunters called 'slayers.' They are capturing our foragers in the swamps. Return their slayer necklaces to me and I shall pay you, but most important, find the slayer captain. Bring me his captain's necklace and I shall give you a secret. I must leave soon. If you need me, just ask Marda where I am.
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_849.png" alt="" /> <a
                                href="/item/13369" data-url="13369" class="tooltip-link link">Frog Eye Necklace</a>) then


>**Emissary Glib says:** Good work. That is one less troll slayer. My people shall learn of your good deed. Please search for the slayer captain. He must be stopped.


Your faction standing with [Oggok Citizen](/faction/143) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+500 exp)

**You receive coin:** 5 <img src='/static/icons/item_644.png' width='14' height='14'/> 7 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_849.png" alt="" /> <a
                                href="/item/13370" data-url="13370" class="tooltip-link link">Frog Eye Necklace</a>) then


>**Emissary Glib says:** 'Oooh!! .. You have dispatched the slayer captain. It will take them time to reorganize the slayers. During this time the froglok foragers can gather more provisions for Guk. Please take this as a token of my people's appreciation. Your standing with my brethren has grown. As for Marda's information.. within Grobb lies my aide, Groak. He was captured. Tell him Glib sent you.


Your faction standing with [Oggok Citizen](/faction/143) got better (<span class='text-success'>+2</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/17928" data-url="17928" class="tooltip-link link">Forager Bag</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_740.png" alt="" /> <a
                                href="/item/13371" data-url="13371" class="tooltip-link link">Hopper Spear</a>) (+500 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**



## Timer(s)

**Emissary Glib despawns.**




