# Tarker Blazetoss
## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then




>**Tarker Blazetoss says:** Hail and well met, Soandso!  Have you come to study, or can you [perform a task] for me this day?


else



**Tarker Blazetoss says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `perform a task`



if **Faction** >= Indifferent then




>**Tarker Blazetoss says:** That is the spirit.  There are many black wolves wandering Faydark these days.  One of my brethren needs a black wolf skin as a component for his magic.  Bring me a black wolf skin, and I shall reward you for your efforts.


else



**Tarker Blazetoss says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18779" data-url="18779" class="tooltip-link link">An Enrollment Letter</a>) then 


>**Tarker Blazetoss says:** Welcome to the wizards' guild of the Keepers of the Art. My name's Tarker, and I run this guild. You've got a lot of training ahead of you, so let's get started. Here, take this - it's our guild tunic. Wear it with honor, friend.


Your faction standing with [Keepers of the Art](/faction/275) got better (<span class='text-success'>+100</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+25</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+15</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_940.png" alt="" /> <a
                                href="/item/13594" data-url="13594" class="tooltip-link link">Singed Training Robe*</a> (+20 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_556.png" alt="" /> <a
                                href="/item/13758" data-url="13758" class="tooltip-link link">Black Wolf Skin</a>) then


>**Tarker Blazetoss says:** This is just what I needed.. and with hardly a mark on it! You have my thanks. Here is a something that you might find useful.


Your faction standing with [Keepers of the Art](/faction/275) got better (<span class='text-success'>+1</span>)


Your faction standing with [King Tearis Thex](/faction/279) got better (<span class='text-success'>+1</span>)


Your faction standing with [Faydarks Champions](/faction/246) got better (<span class='text-success'>+1</span>)


Your faction standing with [The Dead](/faction/239) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7007" data-url="7007" class="tooltip-link link">Rusty Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/6012" data-url="6012" class="tooltip-link link">Worn Great Staff</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15374" data-url="15374" class="tooltip-link link">Spell: Numbing Cold</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_748.png" alt="" /> <a
                                href="/item/10004" data-url="10004" class="tooltip-link link">Copper Band</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/6018" data-url="6018" class="tooltip-link link">Cracked Staff</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_615.png" alt="" /> <a
                                href="/item/10008" data-url="10008" class="tooltip-link link">Gold Ring</a>) (+350 exp)

 

**This NPC *should* return incorrect items given.**
;

