# Kazzel D\`Leryt



[Kazzel D\`Leryt](/npc/50272) is a level 50 Dark Elf Necromancer that spawns in [Rathe Mountains](/zone/50).



## Dialog

**You say:** `hail`



if(**Your level** >= 50) then



>**Kazzel D-Leryt says:** Finally, a servant worthy of my needs! Apparently you are of high status, which perhaps means you might know a master [jeweler] capable of faceting a very magical, yet fragile stone?


else



>**Kazzel D-Leryt says:** Begone you pathetic bug. You are not worthy of my presence.




**You say:** `jeweler`



>**Kazzel D-Leryt says:** You must provide me with  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2000" data-url="2000" class="tooltip-link link">Vale Reinforced Boots</a> platinum pieces as a deposit, then you must take this stone to a master jeweler or [Darfumpel], have it faceted and return it to me along with an orb of pure crystal, a gold necklace the color of snow, and the [blood of Xenyari]. Do that and I will provide you with magic beyond that of most knights of darkness.

**You say:** `darfumpel`



>**Kazzel D-Leryt says:** Darfumpel is a gnomish shopkeeper here in the Rathe Mountains. He apparently has a new technique for gemcutting, however, he will not deal with me due to my affiliation with necromancy. Speak with him. Perhaps he might be willing to aid you for a price, but make sure you hide your true nature. He despises dark magic.

**You say:** `blood of xenyari`



>**Kazzel D-Leryt says:** Xenyari is a druid who inhabits these parts. She is rarely seen, however, I require a droplet of her blood. Here is the catch though, and one for which you may be well suited if you desire magic of the knights of darkness - Xenyari must give of herself willingly. In other words, you cannot take her blood by force. Rather, she must give you her blood of her own accord.
end



## Turn-Ins



local text = "Quickly now, give me the rest of the ingredients for the telesm...";



if(**Your level** >= 50 and  **You turn in:** platinum = <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2000" data-url="2000" class="tooltip-link link">Vale Reinforced Boots</a>) then


>**Kazzel D-Leryt says:** Very well, Soandso. Take this gem to a master jeweler and return it to me with the other three items.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_965.png" alt="" /> <a
                                href="/item/10191" data-url="10191" class="tooltip-link link">Uncut Hyacinth</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_965.png" alt="" /> <a
                                href="/item/10192" data-url="10192" class="tooltip-link link">Faceted Hyacinth</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_752.png" alt="" /> <a
                                href="/item/10147" data-url="10147" class="tooltip-link link">White Gold Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10218" data-url="10218" class="tooltip-link link">Crystalline Orb</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_870.png" alt="" /> <a
                                href="/item/10196" data-url="10196" class="tooltip-link link">Bloodied Piece of Parchment</a>) then


>**Kazzel D-Leryt says:** You are quite cunning. After I fashion this telesm, take it back to Xenyari. She would 'enjoy' another 'gift,' eh?


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_752.png" alt="" /> <a
                                href="/item/10193" data-url="10193" class="tooltip-link link">Faceted Hyacinth Telesm</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_752.png" alt="" /> <a
                                href="/item/10194" data-url="10194" class="tooltip-link link">Pulsating Hyacinth Telesm</a>) then


>*Kazzel D-Leryt laughs heartily and whispers to you, 'Well done, worm, your servitude to my will has now expired...'*


 &#127873; **You receive:** 0 (+25000 exp)

 


**Spawn NPC:**  [a monstrous zombie](/npc/50335) at this location.

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/10197" data-url="10197" class="tooltip-link link">Monstrous Zombie Heart</a>) then


>**Kazzel D-Leryt says:** Oh! Umm... Well, I was just playing with you. Certainly you know I was joking! We had a deal and I will abide by the terms of our agreement. Here is my payment for your services. Bye..


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15692" data-url="15692" class="tooltip-link link">Spell: Life Leech</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**





