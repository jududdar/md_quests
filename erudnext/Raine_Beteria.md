# Raine Beteria
## Dialog

**You say:** `hail`



if( **Faction is** >= Indifferent) then



>**Raine Beteria says:** Welcome. I am Raine Beteria.


else



>**Raine Beteria says:** You are lucky to be standing. Leave here immediately or suffer grave consequences! You are not welcome amongst the Craftkeepers.

end

## Turn-Ins




if( **Faction is** >= Indifferent) then


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/6339" data-url="6339" class="tooltip-link link">Blessed Silver Wand</a>,gold = 50) then



>**Raine Beteria says:** Your silver wand has been fully enchanted. Take it and the pouch of silver dust back to the temple of Ro.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/6340" data-url="6340" class="tooltip-link link">Glowing Silver Wand</a> (+1000 exp)

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/10792" data-url="10792" class="tooltip-link link">Gleaming Coin of Tash</a>) then



>**Raine Beteria says:** Thank you very much. I have always wanted one of these! Hehehe? Just kidding. I see that you have enchanted this coin. I have placed the final enchantment on it - take it back to Romar.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/10793" data-url="10793" class="tooltip-link link">Radiant Coin of Tash</a> (+1000 exp)

 


**This NPC *should* return incorrect items given.**
;