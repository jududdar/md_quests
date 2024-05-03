# Nultal Malfoot


## Dialog

**You say:** `hail`



>**Nultal Malfoot says:** May the power of Underfoot be with you. Welcome. I am here to serve the will of the king as should you. If you [need healing], then speak. Or perhaps you are here to [return skunk glands]?

**You say:** `healing`



if **Faction** >= Indifferent then



>**Nultal Malfoot says:** Before the power of Underfoot can attempt to bind your wounds you must pay tribute. Three gold coins!!


else



>**Nultal Malfoot says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!


**You say:** `glands`



if **Faction** >= Amiable then



>**Nultal Malfoot says:** I have made an offer to all clerics of this cathedral. I shall reward one cleric scroll from our scribes for the return of four skunk scent glands. This offer is best left to our clerics.


elseif **Faction** >= Indifferent then



>**Nultal Malfoot says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


else



>**Nultal Malfoot says:** How dare you approach a member of the Clerics of Underfoot?!  Dogs such as you lie in the same bed as aviaks and ogres!

end



## Turn-Ins



local text = "There shall be no scroll until I see four skunk scent glands.";



if **Faction** >= Indifferent and  **You turn in:** gold = 3) then


>**Nultal Malfoot says:** Be healed!


**Nultal Malfoot casts:** [Light Healing](/spell/17) on target.


elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/14030" data-url="14030" class="tooltip-link link">Skunk Scent Gland</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/14030" data-url="14030" class="tooltip-link link">Skunk Scent Gland</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/14030" data-url="14030" class="tooltip-link link">Skunk Scent Gland</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_820.png" alt="" /> <a
                                href="/item/14030" data-url="14030" class="tooltip-link link">Skunk Scent Gland</a>) then 


>**Nultal Malfoot says:** I thank you for your good deed. I trust it was not a problem. Take this scroll. A cleric of this cathedral will find it useful. May the power of Underfoot be with you.


Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+5</span>)





Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+5</span>)




Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+3</span>)




 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15203" data-url="15203" class="tooltip-link link">Spell: Cure Poison</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15229" data-url="15229" class="tooltip-link link">Spell: Fear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15560" data-url="15560" class="tooltip-link link">Spell: Furor</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15036" data-url="15036" class="tooltip-link link">Spell: Gate</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15216" data-url="15216" class="tooltip-link link">Spell: Stun</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15215" data-url="15215" class="tooltip-link link">Spell: Reckless Strength</a>) (+5000 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-10 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
