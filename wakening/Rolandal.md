# Rolandal



[Rolandal](/npc/119104) is a level 60 Dragon Warrior that spawns in [The Wakening Land](/zone/119).



## Dialog

**You say:** `hail`



if **Faction** >= Warmly then



>**Rolandal says:** Greetings, Traveler. I do not receive many visitors to my quarters here, besides the occasional unfortunate treasure seeker that often will make for a good snack.


elseif **Faction** >= Indifferent then



>**Rolandal says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Rolandal says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `kardakor`



if **Faction** >= Warmly then



>**Rolandal says:** You are sent from Kardakor are you? Well surely he must have sent you to stand before me for a reason.


elseif **Faction** >= Indifferent then



>**Rolandal says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Rolandal says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `talisman`



if **Faction** >= Warmly then



>**Rolandal says:** Ah of course, It has been quite a long time sense my powers of identification have been requested. If you are sent from Kardakor then your intent must be well directed. I do have a favor to ask of you before I identify your talisman. I seek some rare treasures to further some studies that I have been working on for a long time.


elseif **Faction** >= Indifferent then



>**Rolandal says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Rolandal says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `rare treasure`



if **Faction** >= Warmly then



>**Rolandal says:** There are 3 items that I seek to continue my studies of some various and musterious magics. Bring to me the teachings of a high ranking Kromzek that I hear goes by the name of Gkrean, a chipped fang from a beast deep within the Cursed Necropolis. Also for good measure, I require the Head of a Kromzek Staff Sergeant to prove to your dedication to our cause. Present these 3 items to me along with your Talisman that you wish to learn more about and I shall do my best to identify its origin for you.


elseif **Faction** >= Indifferent then



>**Rolandal says:** You need to prove your dedication to our cause before I can discuss such matters with you.




else



**Rolandal says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins





if **Faction** >= Warmly and ( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/1861" data-url="1861" class="tooltip-link link">An old worn Talisman</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/1864" data-url="1864" class="tooltip-link link">Teachings of Gkrean</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/1865" data-url="1865" class="tooltip-link link">Head of Staff Sergeant Drioc</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1240.png" alt="" /> <a
                                href="/item/1863" data-url="1863" class="tooltip-link link">A chipped fang</a> or  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_860.png" alt="" /> <a
                                href="/item/1864" data-url="1864" class="tooltip-link link">Teachings of Gkrean</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/1865" data-url="1865" class="tooltip-link link">Head of Staff Sergeant Drioc</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1240.png" alt="" /> <a
                                href="/item/1863" data-url="1863" class="tooltip-link link">A chipped fang</a>)) then


>**Rolandal says:** So you finally made it ! Head back to Ralgyn to get your reward.


Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+50</span>)


Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+12</span>)


Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-25</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/1866" data-url="1866" class="tooltip-link link">Glanitar's Imbued Talisman</a> (+10000 exp)

 


**Rolandal despawns.**

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/1861" data-url="1861" class="tooltip-link link">An old worn Talisman</a>) then


>**Rolandal says:** It would be my guess that you present this to me in hopes of finding out more about the magics it possesses. Before I can do this I require some rare treasures that you must present to me.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/1861" data-url="1861" class="tooltip-link link">An old worn Talisman</a> 

 


**This NPC *should* return incorrect items given.**
