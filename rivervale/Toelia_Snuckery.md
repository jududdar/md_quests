# Toelia Snuckery
## Dialog

**You say:** `hail`



>**Toelia Snuckery says:** Oh, hi.  Listen, um.. Soandso, was it?  Listen, pal.  I really don't have time for the friendly-friendly, so why don't you just move on?

**You say:** `dishwasher`



if **Faction** >= Amiable then



>**Toelia Snuckery says:** Dishwasher, huh?  You must not mind getting your feet wet then, huh?  Well, I do have a job for you.  It seems one of our younger employees got a little nevous around a Deputy and ditched his um..  recent purchase into the river.  We sent the fool after it but ol' [Chomper] got him.  He said he had dropped it off the docks but the currents might have moved it from there.  It should be in an old pouch.  Return the merchandise to me.  Well?  Get going!


elseif **Faction** >= Indifferent then



>**Toelia Snuckery says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Toelia Snuckery says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!



**You say:** `chomper`



if **Faction** >= Amiable then




>**Toelia Snuckery says:** Chomper is a big, mean ol' fish.  He looks like a normal fish, but a little bigger, and boy, oh boy, is he mean!




elseif **Faction** >= Indifferent then



>**Toelia Snuckery says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Toelia Snuckery says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/13785" data-url="13785" class="tooltip-link link">Torn Old Pouch</a>) then 


>**Toelia Snuckery says:** What is this? The pouch is empty!  Where is the Ruby?! What do you mean you don't have it? Oh no. I bet [Chomper] swallowed it! Get it back and bring it to me.





Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+5</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+1</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/13786" data-url="13786" class="tooltip-link link">Large Ruby</a>) then 


>**Toelia Snuckery says:** You found it! Heh. Good thing you brought it back bub. This thing isn't priceless, its worthless but at least you proved you are loyal. Poor ol' Chomper..





Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+10</span>)


Your faction standing with [Circle of Unseen Hands](/faction/223) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Rivervale](/faction/292) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got better (<span class='text-success'>+1</span>)


Your faction standing with [Carson McCabe](/faction/329) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+1000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**


