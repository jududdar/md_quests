# Syllina


## Dialog

**You say:** `Hail`



>**Syllina says:** Hello, I am Syllina, follower of Solusek Ro and keeper of the [Shadow Lore].

**You say:** `lore`



>**Syllina says:** I hold the secrets to the Shadow Lore so highly prized by Necromancers. If you are interested, I can tell you about [ShadowBound Boots], [ShadowBound Gloves], the [Robe of Enshroudment] or the secrets to the making of [Shadow Silk].

**You say:** `shadowbound boots`



>**Syllina says:** ShadowBound Boots are boots woven from purest shadow. If you are interested, I will weave you a pair - but I will need [boot components].

**You say:** `boot components`



>**Syllina says:** I will need the following items to make you a pair of ShadowBound Boots: Shadow Silk, The Scepter of Sorrow from Castle Mistmoore, an Eye of Shadow from our mortal enemies the Shadowed Men and a Skeletal toe from a Rathe Giant Skeleton.

**You say:** `shadowbound gloves`



>**Syllina says:** ShadowBound Gloves are gloves woven from the purest shadow. If you are interested, I will weave you a pair - but I will need [glove components].

**You say:** `glove components`



>**Syllina says:** I will need the following items to make you a pair of ShadowBound Gloves: Inky Shadow Silk, The Scepter of Tears from the circle-stair-waterfall of Guk, a Hand of Shadow from our mortal enemies the Shadowed Men and a Skeletal finger from a Rathe Giant Skeleton.

**You say:** `robe of enshroudment`



>**Syllina says:** The Robe of Enshroudment is a robe woven from the purest of shadow. If you are interested, I will weave you a robe - but I will need the following [robe components].

**You say:** `robe components`



>**Syllina says:** I will need the following items to make you a Robe of Enshroudment: Large Shadow Silk, A Werebat Wing from the Estate of Unrest, A Mask of Shadow from our mortal enemies the Shadowed Men and a Globe of Shadow from a Nokta Shaman in Guk.

**You say:** `shadow silk`



>**Syllina says:** If you are interested, I will tell you the secrets of making Shadow Silk for a mere 50 pieces of gold.
end

## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";





if( **You turn in:** gold = 50) then


>**Syllina says:** You will need to give the following components to a tailor: a Shadow Wolf Pelt, a Silk Swatch and a Scroll of Gather Shadows. Have the tailor weave them together and she will make you Shadow Silk. To make large shadow silk add an extra shadow wolf pelt. To make inky shadow silk, add an extra scroll.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+1</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)



elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/16484" data-url="16484" class="tooltip-link link">Large Shadow Silk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_791.png" alt="" /> <a
                                href="/item/13239" data-url="13239" class="tooltip-link link">A Werebat Wing</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2309" data-url="2309" class="tooltip-link link">Mask of Shadow</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10535" data-url="10535" class="tooltip-link link">Globe of Shadow</a>) then


>**Syllina says:** Silk, wing, mask, globe... all of the components necessary for the making of a robe of Enshroudment. Well done. Here is your reward.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1126.png" alt="" /> <a
                                href="/item/1355" data-url="1355" class="tooltip-link link">Robe of Enshroudment</a> (+1000 exp)

 



elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_821.png" alt="" /> <a
                                href="/item/14363" data-url="14363" class="tooltip-link link">A Scepter</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_971.png" alt="" /> <a
                                href="/item/13234" data-url="13234" class="tooltip-link link">Hand of Shadow</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/10534" data-url="10534" class="tooltip-link link">A skeletal finger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/16485" data-url="16485" class="tooltip-link link">Inky Shadow Silk</a>) then


>**Syllina says:** So you have gathered all of the components for me to weave Shadowbound Gloves... Well done. You will be wanting these.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/3318" data-url="3318" class="tooltip-link link">ShadowBound Gloves</a> (+1000 exp)

 



elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_821.png" alt="" /> <a
                                href="/item/14364" data-url="14364" class="tooltip-link link">A Scepter</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_885.png" alt="" /> <a
                                href="/item/13180" data-url="13180" class="tooltip-link link">Eye of Shadow</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/10533" data-url="10533" class="tooltip-link link">A skeletal toe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/16483" data-url="16483" class="tooltip-link link">Shadow Silk</a>) then


>**Syllina says:** I see that you have gathered all of the necessary components... Well done. Here are your Shadowbound Boots.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/3317" data-url="3317" class="tooltip-link link">ShadowBound Boots</a> (+1000 exp)

 
end
