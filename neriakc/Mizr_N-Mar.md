# Mizr N\`Mar



[Mizr N\`Mar](/npc/42011) is a level 40 Dark Elf Shopkeeper that spawns in [Neriak - 3rd Gate](/zone/42).





## Dialog

**You say:** `hail`



>**Mizr N-Mar says:** Have you come to buy a scroll from me?

**You say:** `coin`



>**Mizr N-Mar says:** So, you want a coin do you?
end



## Turn-Ins




if( **You turn in:** gold = 50) then


>**Mizr N-Mar says:** Ahhh - gold. Here is the rune you desire.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10531" data-url="10531" class="tooltip-link link">Rune of Fortune</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/10791" data-url="10791" class="tooltip-link link">Glowing Coin of Tash</a>) then


>**Mizr N-Mar says:** Ah - the Coin of Tash - and already enchanted by.. ? Tarn? Very good! I have enchanted it further - you must now take the coin to Raine Beteria in the Library of Erudin to get the final enchantment.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/10792" data-url="10792" class="tooltip-link link">Gleaming Coin of Tash</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
