# Cryssia Stardreamer




## Dialog

if **Faction** >= Indifferent then



**You say:** `hail`




>**Cryssia Stardreamer says:** Well met Soandso. I am Cryssia Stardreamer of the Temple of Solusek Ro, protector of a powerful armor that will aid any bard in their journey across Norrath.  Are you a bard that desires this armor?


**You say:** `no`




>**Cryssia Stardreamer says:** Very well then.


**You say:** `yes`




>**Cryssia Stardreamer says:** Very well. I can craft a special type of bardic armor called lambent.  I can craft for you a set of [bracers], a [breastplate], a [helm], and [vambraces]. I require a special kind of lambent stone for each of my armor pieces.  Find my friends Orstorm, Genni, Gardern, and Vilissia within the temple and they will help you create them.


**You say:** `bracers`




>**Cryssia Stardreamer says:** Alright, I will be needing some items. Return to me with them and I will craft your bracers. I will be needing a Dark Boned Bracelet, a Griffenne Charm, and a Lambent Fire Opal.


**You say:** `breastplate`




>**Cryssia Stardreamer says:** This is the most difficult piece to make. In order for me to craft it I will be needing a Basalt Carapace, a Gypsy Lute, and a Lambent Ruby. Return to me with these and I will craft your breastplate.


**You say:** `helm`




>**Cryssia Stardreamer says:** In order to craft the helm, I will be needing a Mudwater Rune, an Opoline Helm, and a Lambent Star Ruby. Give these items to me and I will craft your helm


**You say:** `vambraces`




>**Cryssia Stardreamer says:** Very good, get me some Fiery Vambraces, the top portion of the Rune of the One Eye, and a Lambent Sapphire.


else


**Cryssia Stardreamer says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins



local text = "Wait, Soandso, are you not forgetting something?";


if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_505.png" alt="" /> <a
                                href="/item/10564" data-url="10564" class="tooltip-link link">Dark Boned Bracelet</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1056.png" alt="" /> <a
                                href="/item/10563" data-url="10563" class="tooltip-link link">Griffenne Charm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/10128" data-url="10128" class="tooltip-link link">Lambent Fire Opal</a>) then


>**Cryssia Stardreamer says:** Good show, Soandso, here is your lambent bracer


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4156" data-url="4156" class="tooltip-link link">Lambent Bracers</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_927.png" alt="" /> <a
                                href="/item/4100" data-url="4100" class="tooltip-link link">Basalt Carapace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_551.png" alt="" /> <a
                                href="/item/10565" data-url="10565" class="tooltip-link link">Consortium Mandolin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_964.png" alt="" /> <a
                                href="/item/10118" data-url="10118" class="tooltip-link link">Lambent Ruby</a>) then


>**Cryssia Stardreamer says:** Exceptionally well done, Soandso, here is your lambent breastplate. Wear it with pride.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/4154" data-url="4154" class="tooltip-link link">Lambent Breastplate</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10559" data-url="10559" class="tooltip-link link">Mudwater Rune</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_550.png" alt="" /> <a
                                href="/item/4099" data-url="4099" class="tooltip-link link">Opoline Helm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/10117" data-url="10117" class="tooltip-link link">Lambent Star Ruby</a>) then


>**Cryssia Stardreamer says:** Well done, Soandso, here is your lambent helm. Wear it with the praises of the League of Antonican Bards.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4153" data-url="4153" class="tooltip-link link">Lambent Helm</a> (+1000 exp)

 

elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_543.png" alt="" /> <a
                                href="/item/4113" data-url="4113" class="tooltip-link link">Fiery Vambraces</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10560" data-url="10560" class="tooltip-link link">Rune of the One Eye</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/10119" data-url="10119" class="tooltip-link link">Lambent Sapphire</a>) then


>**Cryssia Stardreamer says:** Excellent, Soandso, you have proved yourself most resourceful. Here are your lambent vambraces.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+10</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_622.png" alt="" /> <a
                                href="/item/4155" data-url="4155" class="tooltip-link link">Lambent Vambraces</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**





