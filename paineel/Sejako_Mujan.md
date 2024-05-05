# Sejako Mujan



[Sejako Mujan](/npc/75117) is a level 40 Erudite Necromancer that spawns in [Paineel](/zone/75).



## Dialog

**You say:** `Hail`



>**Sejako Mujan says:** Shhhh....keep your voice down lest you wake Alaria. We can [speak elsewhere] if you wish.

**You say:** `speak elsewhere`



>**Sejako Mujan says:** Follow me and we shall discuss how you may assist me with my [current research].


eq.start(16);

**You say:** `current research`



>**Sejako Mujan says:** Recently patrols have been sent to the Stonebrunt Mountains to investigate rumors of an alliance between the Kejekans and Erudin. There is much spiritual activity in that region of Odus and the patrols have reported encountering massive beasts called Titans. These titans exhibit abilities that lead me to believe they are powerful animal spirits that have somehow taken on a physical form in order to enter and manipulate the realm of the living. I require [samples] of the Titans physiology in order to further my research.

**You say:** `samples`



>**Sejako Mujan says:** There have been sightings of Titans in many forms. The samples I require are the fangs of the leopard, sabretooth, and gorilla titans, and the rattle of the snake titan.
end



## Turn-Ins



local text = "I require all four titan samples in order to pursue the research I desire.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1137.png" alt="" /> <a
                                href="/item/6957" data-url="6957" class="tooltip-link link">Gigantic Gorilla Fang</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1137.png" alt="" /> <a
                                href="/item/6943" data-url="6943" class="tooltip-link link">Giant Sabertooth Fang</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1137.png" alt="" /> <a
                                href="/item/6959" data-url="6959" class="tooltip-link link">Giant Leopard Fang</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1122.png" alt="" /> <a
                                href="/item/6948" data-url="6948" class="tooltip-link link">Ancient Snake Rattle</a>) then


>**Sejako Mujan says:** Excellent!! These shall provide valuable information to my research on the spirit realm.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/2568" data-url="2568" class="tooltip-link link">Staff of the Moribund Spirits</a> (+250 exp)

 

**This NPC *should* return incorrect items given.**




