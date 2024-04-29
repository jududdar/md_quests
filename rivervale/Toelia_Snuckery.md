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




if **Faction** >= Amiable and  **You turn in:** [Torn Old Pouch](/item/13785)) then 


>**Toelia Snuckery says:** What is this? The pouch is empty!  Where is the Ruby?! What do you mean you don't have it? Oh no. I bet [Chomper] swallowed it! Get it back and bring it to me.





* __Faction:__ [Deeppockets](/faction/241) (5)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (-1)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)


* __Faction:__ [Carson McCabe](/faction/329) (1)


 **You receive:** 0 (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Large Ruby](/item/13786)) then 


>**Toelia Snuckery says:** You found it! Heh. Good thing you brought it back bub. This thing isn't priceless, its worthless but at least you proved you are loyal. Poor ol' Chomper..





* __Faction:__ [Deeppockets](/faction/241) (10)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (-1)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)


* __Faction:__ [Carson McCabe](/faction/329) (1)


 **You receive:** 0 (+1000 exp)

**This NPC *should* return incorrect items given.**


