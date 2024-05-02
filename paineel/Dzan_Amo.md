# Dzan Amo
## Dialog

if **Faction** >= Apprehensive then 


**You say:** `hail`




>**Dzan Amo says:** Welcome to the Tabernacle of Terror. Perhaps you can control your fear long enough to be of [service] to us.


**You say:** `service`




>**Dzan Amo says:** I need some things fetched from the creatures just outside our city for some ritual experimentation. Bring me two tufts of bat fur and two fire beetle legs and I will school you in the ways of terror.


else


>**Dzan Amo says:** Begone from this place! Infidels like you have no place among the faithful of Cazic-Thule!

end

## Turn-Ins



local text = "I need no fewer than four infected rat livers!! Now, go get me what I require!!"; 



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_792.png" alt="" /> <a
                                href="/item/13069" data-url="13069" class="tooltip-link link">Bat Fur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_792.png" alt="" /> <a
                                href="/item/13069" data-url="13069" class="tooltip-link link">Bat Fur</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1089.png" alt="" /> <a
                                href="/item/13250" data-url="13250" class="tooltip-link link">Fire Beetle Leg</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1089.png" alt="" /> <a
                                href="/item/13250" data-url="13250" class="tooltip-link link">Fire Beetle Leg</a>) then 


>**Dzan Amo says:** Very good young one. Here is something to assist in your studies of the principles of terror.


Your faction standing with [Heretics](/faction/265) got better (<span class='text-success'>+5</span>)


Your faction standing with [Deepwater Knights](/faction/242) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Gate Callers](/faction/254) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Craftkeepers](/faction/231) got worse (<span class='text-danger'>-5</span>)


Your faction standing with [Crimson Hands](/faction/233) got worse (<span class='text-danger'>-5</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15209" data-url="15209" class="tooltip-link link">Spell: Spook the Dead</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**






