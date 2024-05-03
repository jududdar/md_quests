# a dwarven slave


## Dialog

**You say:** `hail`



>**a dwarven slave says:** Slavedrivers are just lackeys for the [taskmaster]. He is the real orc in charge.

**You say:** `taskmaster`



>**a dwarven slave says:** The taskmaster?? He is that large orc who runs around with that [bronze earring] in his ear.

**You say:** `bronze earring`



>**a dwarven slave says:** Yeah, a bronze earring; He wears it like a newly crowned king. If I ever had that earring I know I would stand a chance at escape.
end



## Turn-Ins






if(e.self:GetRace() == 8 and e.self:GetGender() == 0) then 


if( **You turn in:** copper = 1) then



>**a dwarven slave says:** No, no!! I do not need this!! Get me key number 16!!


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1079.png" alt="" /> <a
                                href="/item/20016" data-url="20016" class="tooltip-link link">Shackle Key 16</a>) then



>**a dwarven slave says:** Good work!! I shall be on my way. Farewell my friend!!



Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+2</span>)



Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+2</span>)



Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:** 0 (+800 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-2 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 



**a dwarven slave despawns.**


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_757.png" alt="" /> <a
                                href="/item/10351" data-url="10351" class="tooltip-link link">Brass Earring</a>) then



>**a dwarven slave says:** You killed the taskmaster?!  Absolutely amazing! The orcs will be fighting among themselves for power now and I can disappear in the commotion. Thanks, friend! Take this for your deeds!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18905" data-url="18905" class="tooltip-link link">A Worn Rune</a> (+5000 exp)

 



**a dwarven slave despawns.**




elseif(e.self:GetRace() == 8 and e.self:GetGender() == 1) then 


if( **You turn in:** copper = 1) then



>**a dwarven slave says:** What is this!!? Get me key number 17!!


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1077.png" alt="" /> <a
                                href="/item/20017" data-url="20017" class="tooltip-link link">Shackle Key 17</a>) then



>**a dwarven slave says:** Good work!! I shall be on my way. Farewell my friend!!



Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+2</span>)



Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+1</span>)



Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+1</span>)



Your faction standing with [Merchants of Kaladim](/faction/290) got better (<span class='text-success'>+1</span>)



Your faction standing with [Craknek Warriors](/faction/232) got worse (<span class='text-danger'>-1</span>)



 &#127873; **You receive:** 0 (+800 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-2 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-5 <img src='/static/icons/item_647.png' width='14' height='14'/> 



**a dwarven slave despawns.**


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_757.png" alt="" /> <a
                                href="/item/10351" data-url="10351" class="tooltip-link link">Brass Earring</a>) then



>**a dwarven slave says:** You killed the taskmaster?!  Absolutely amazing! The orcs will be fighting among themselves for power now and I can disappear in the commotion. Thanks, friend! Take this for your deeds!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18906" data-url="18906" class="tooltip-link link">A Small Wood Carving</a> (+5000 exp)

 



**a dwarven slave despawns.**




**This NPC *should* return incorrect items given.**
;