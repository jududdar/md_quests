# Karam Dragonforge



[Karam Dragonforge](/npc/50269) is a level 45 Dwarf Shopkeeper that spawns in [Rathe Mountains](/zone/50).



## Dialog

**You say:** `hail`



>**Karam Dragonforge says:** Welcome. I have a number of platemail items, if you are interested. I am also a master [smith] of exotic materials such as dragon scales.

**You say:** `smith`



if **Faction** >= Indifferent then



>**Karam Dragonforge says:** Dragon scales make terrific armor. I can make a [white dragonscale cloak] and [red dragonscale armor]. I have not seen any other colored dragon variants around. But if you see any, be sure to let me know. I would be interested in what can be made from their scales.


else



**Karam Dragonforge says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `white dragonscale cloak`



if **Faction** >= Indifferent then



>**Karam Dragonforge says:** Hrmmm. A white dragonscale cloak eh? Hrmmm. Well, I will make you a deal. You can save me some footwork and I will craft your cloak. I want to propose to my [fiancee] but I have neither a [wedding ring] nor a [present] for her. So, return with a white dragon hide, a wedding ring, and a present for my fiancee, and I will fashion your cloak for you.


else



**Karam Dragonforge says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `fiancee`



if **Faction** >= Indifferent then



>**Karam Dragonforge says:** My fiancee...AHHHH.... The love of my life. My purpose for existing. She is a real woman. Long, golden blonde hair with a similarly colored full beard. A stout broad she is, kind and warm at heart. She knows every nook of my essence. But do not let that fool you. She is as strong as many dwarven men. Between you and me, she has even beaten me once or twice arm-wrestling over who gets the last ale and who has to go to the market.


else



**Karam Dragonforge says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `wedding ring`



if **Faction** >= Indifferent then



>**Karam Dragonforge says:** Only the best will do. I will not propose to her with anything less than a platinum and diamond wedding ring.


else



**Karam Dragonforge says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `present`



if **Faction** >= Indifferent then



>**Karam Dragonforge says:** Well, she is quite fond of jewelry. And a black sapphire platinum necklace would complement her eyes and beard so exquisitely.


else



**Karam Dragonforge says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `red dragonscale armor`



if **Faction** >= Indifferent then



>**Karam Dragonforge says:** So you have a red dragon scale, eh? Well, I am wanting very much to return to my fiancee and propose to her. If you could aid me in quickly returning to her with a bit of spare change, we could have a deal. Heck, for the armor, a vial of swirling smoke and 1000 platinum coins is a bargain!


else



**Karam Dragonforge says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end



## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1064.png" alt="" /> <a
                                href="/item/14707" data-url="14707" class="tooltip-link link">Platinum Diamond Wedding Ring</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1043.png" alt="" /> <a
                                href="/item/14703" data-url="14703" class="tooltip-link link">Black Sapphire Platinum Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_552.png" alt="" /> <a
                                href="/item/9240" data-url="9240" class="tooltip-link link">White Dragon Hide</a>) then


>**Karam Dragonforge says:** My fiancee will be so excited! An exquisite ring for the wedding and a gorgeous necklace as my wedding gift to her. Well, as promised, here is your white dragonscale cloak.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_657.png" alt="" /> <a
                                href="/item/11603" data-url="11603" class="tooltip-link link">White Dragonscale Cloak</a> 

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1088.png" alt="" /> <a
                                href="/item/11622" data-url="11622" class="tooltip-link link">Red Dragon Scales</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_695.png" alt="" /> <a
                                href="/item/14402" data-url="14402" class="tooltip-link link">Vial of Swirling Smoke</a>, platinum = 1000) then


>**Karam Dragonforge says:** Wonderful! Now I can get back to my fiancee instantly! Isn't Love grand? As for your Red Dragonscale Armor, it is all done. Farewell!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_621.png" alt="" /> <a
                                href="/item/11623" data-url="11623" class="tooltip-link link">Red Dragonscale Armor</a> 

 

**This NPC *should* return incorrect items given.**





