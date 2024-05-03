# Vurgo


## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Vurgo says:** Welcome! I am Vurgo, follower of Solusek Ro and holder of the [harvester] and the [Words of Darkness].


**You say:** `harvester`




>**Vurgo says:** I can forge you one, but you will need to bring me the correct [scythe components].


**You say:** `scythe components`




>**Vurgo says:** The first thing I need is a shadowed scythe from our mortal enemies, the shadowed men.


**You say:** `words of darkness`




>**Vurgo says:** I can scribe for you the Words of Darkness, but you will need to bring me the correct [word components].


**You say:** `word components`




>**Vurgo says:** The first thing that I need is a shadowed book from our mortal enemies, the shadowed men.


else


**Vurgo says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";


if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_579.png" alt="" /> <a
                                href="/item/5103" data-url="5103" class="tooltip-link link">Shadowed Scythe</a>) then


>**Vurgo says:** A shadowed scythe! Well done! The only good shadowed man is a banished one. As the weapons of the shadowed men have a tendency to disappear, I have given you a note to remind me that you have indeed supplied me with a scythe. Give me the note with the following items and I will forge you a harvester: a fungus eye from a mortuary fungus in the Estate of Unrest, a shadowed knife from an island goblin headmaster in the Ocean of Tears and a fire opal. Give me these items, and I will forge for you a harvester.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18944" data-url="18944" class="tooltip-link link">A note</a> (+500 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/10529" data-url="10529" class="tooltip-link link">Shadowed Book</a>) then


>**Vurgo says:** A shadowed book! Well done! The more banished shadowed men the better. As the items of the shadowed men tend to disappear, I have given you a note to remind me that you have indeed supplied me with a book. Give me the note with the following items, and I will scribe for you Words of Darkness: a book of darkness from the Erudites in the tower by Lake Rathe, a book of frost from the icy goblin in Permafrost Keep and 300 golden coins. Bring me these items, and I will scribe for you the Words of Darkness.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18945" data-url="18945" class="tooltip-link link">A note</a> (+500 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_885.png" alt="" /> <a
                                href="/item/10538" data-url="10538" class="tooltip-link link">A fungus eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/10031" data-url="10031" class="tooltip-link link">Fire Opal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7331" data-url="7331" class="tooltip-link link">A shadowed knife</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18944" data-url="18944" class="tooltip-link link">A note</a>) then 


>**Vurgo says:** My note, a fungus eye, a shadowed knife and gold! All of the necessary components to make a harvester. Well done, adventurer!


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_579.png" alt="" /> <a
                                href="/item/5316" data-url="5316" class="tooltip-link link">Harvester</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/10536" data-url="10536" class="tooltip-link link">Book of Darkness</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_777.png" alt="" /> <a
                                href="/item/10537" data-url="10537" class="tooltip-link link">Book of Frost</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18945" data-url="18945" class="tooltip-link link">A note</a>,gold = 300) then 


>**Vurgo says:** All of the necessary components for me to scribe the Words of Darkness! Very good, adventurer. Take your tome, you have earned it.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_789.png" alt="" /> <a
                                href="/item/10527" data-url="10527" class="tooltip-link link">Words of Darkness</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
