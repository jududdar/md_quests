# Ritap



[Ritap](/npc/110053) is a level 31 Gnome Rogue that spawns in [Iceclad Ocean](/zone/110).



## Dialog

**You say:** `hail`



>**Ritap says:** Avast you! Ya best be shovin off if ye know whats good for you.  We be pirate raiders and ya best not be messin with the likes of us!


if(**spawned NPC:**  [Ratop](/npc/110052)) then



eq.get_entity_list():GetMobByNpcTypeID( [Ratop](/npc/110052)):Say("Squawk! Pieces of eight! Pieces of eight!");



>**Ritap says:** The cap'n said PIRATES! Not parrots ye knucklehead!' He whacks the other raider upside the head. 'now whars the tinkered rope!?'



eq.get_entity_list():GetMobByNpcTypeID( [Ratop](/npc/110052)):Say("We be out.  Youll be needin to make more. Arg!");


**You say:** `tinkered rope`



>**Ritap says:** Batten down yer yapper! Ahl be doin the talkin here.   We be needin the rope to tie ye down fer ransom.  Now fetch me the beard of a frost giant scout so's I can make some more rope to tie ye up with.
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1001.png" alt="" /> <a
                                href="/item/30048" data-url="30048" class="tooltip-link link">Frost Giant Scout Beard</a>) then


>**Ritap says:** Arg! By blubberbeards nostril!  Ye'v done it!'  He braids the beard together into a sturdy rope. 'Now take this here rope and tie yerself up!  Come lets go tell the cap'n we'v captured us some prisoners!'


Your faction standing with [Pirates of Iceclad](/faction/447) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_572.png" alt="" /> <a
                                href="/item/30049" data-url="30049" class="tooltip-link link">Tinkered Rope</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
