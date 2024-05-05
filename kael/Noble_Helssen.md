# Noble Helssen



[Noble Helssen](/npc/113108) is a level 55 Giant Wizard that spawns in [Kael Drakkel](/zone/113).



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Noble Helssen says:** You obviously have no idea where you have trespassed so I will generously allow you to live. I suggest you leave immediately before my generosity runs out however......Unless, you're looking for work.


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `looking for work`



if **Faction** >= Indifferent then



>**Noble Helssen says:** Well, you might do. Out in the deepest scar, known as the Wakening Land we have deployed several mercenaries to harass the local annoying population. They are in need of constant supplies so we hire those we can trust to deliver those supplies to the mercenaries wandering out in the field. Are you interested, " .. e.other:Race() .. "?


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `interested`



if **Faction** >= Indifferent then



>**Noble Helssen says:** Very well. Take this pack of supplies to any of the Mercenaries you come across in the field. They will pay you upon delivery. Return here for more supplies to deliver when you are ready.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_690.png" alt="" /> <a
                                href="/item/1724" data-url="1724" class="tooltip-link link">Field Supplies</a>


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `plane of growth`



if **Faction** >= Indifferent then



>**Noble Helssen says:** Our soldiers fell victim to the denizens of that plane and unless we can find some way to stop this from happening, the land of Wakening will never be under our control. Many have suggested just destroying the Nexus but they are short-sighted fools. My vision is not only to control the resources that forest provides, but also to control the very force of Growth itself! You will help me to do this, mercenary.


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.


**You say:** `help you`



if **Faction** >= Indifferent then



>**Noble Helssen says:** The tablet I have given you is inscribed with runes of binding. I am owed a favor and it has come time to use it. There is a venerable sea turtle that lives along the warmer part of the coast, where the ice floes begin to break up. His name is Corudoth. Find him and speak with him. Remind him of his obligation to me and if he is not forthcoming in his answers, tell him he owes me. Then show him the tablet. He will tell you what to do. He will most likely be beneath the ocean.  The mask I gave you should help.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_528.png" alt="" /> <a
                                href="/item/1713" data-url="1713" class="tooltip-link link">Enchanted Velium Mask</a>


else



**Noble Helssen says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

end



## Turn-Ins



local text = "I have much to do, Soandso. Do not waste my time unless you have the Arcanum AND the key to open it.";



if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/1709" data-url="1709" class="tooltip-link link">Report of Failure</a>) then 


>*Noble Helssen takes the report from you and places it in a pocket without even glancing at it. He says, 'Do not worry, Soandso. I know of the planar creatures who eliminated my troops. The fault is not yours but of that fool Drioc's. The Savage land is not just a simple forest as those idiots in the field believe. It is a cradle of life and the forces that drive it. Within that forest is a nexus, a gateway to another plane of existence, the Plane of Growth.'*





Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+15</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+3</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+3</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-7</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_972.png" alt="" /> <a
                                href="/item/1710" data-url="1710" class="tooltip-link link">Inscribed Velium Tablet</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_867.png" alt="" /> <a
                                href="/item/1722" data-url="1722" class="tooltip-link link">Helssen's Voucher</a>) then 


>**Noble Helssen says:** Excellent choice, " .. e.other:Race() .. ". Competence and a sense of style. When we are ready to take the Wakening I will most definitely welcome your participation. Here is your reward.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_512.png" alt="" /> <a
                                href="/item/1723" data-url="1723" class="tooltip-link link">Noble's Seal</a> (+2000 exp)

 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_534.png" alt="" /> <a
                                href="/item/1720" data-url="1720" class="tooltip-link link">Helssen's Prismatic Trinket</a> 

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/1712" data-url="1712" class="tooltip-link link">Arcanum of Rosh</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1079.png" alt="" /> <a
                                href="/item/1714" data-url="1714" class="tooltip-link link">Ancient Rusted Key</a>) then 


>**Noble Helssen says:** Ahhh, you suprise me mercenary. You have found the book as well as the key to open it. I must begin my research as soon as possible. But first, your reward. With this voucher you can receive 1 of the 3 treasures I will offer you. If given to Kellek you will receive an item worthy of a hearty and rugged combatant. If given to Wenglawks you will aquire an item to be worn by only the most pious. And if given to me I will give you a sorcerous trinket of my own design.


Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+11</span>)


Your faction standing with [Kromrif](/faction/419) got better (<span class='text-success'>+5</span>)


Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+5</span>)


Your faction standing with [Claws of Veeshan](/faction/430) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_867.png" alt="" /> <a
                                href="/item/1722" data-url="1722" class="tooltip-link link">Helssen's Voucher</a> (+2000 exp)

 

**This NPC *should* return incorrect items given.**
