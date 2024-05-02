# Bella Stremi
## Dialog

**You say:** `hail`



>**Bella Stremi says:** Ah hello and welcome, Soandso. 'Tis a pleasure to see some new faces.  I have the finest wares to be found, be sure to check them out.

**You say:** `wares`



>**Bella Stremi says:** Oh I carry the usual items, food and various other things. I may have something you would be interested in if you are a practitioner of the dark arts.

**You say:** `dark art`



>**Bella Stremi says:** Frantip and I once accepted in trade this set of armor from a necromancer for services rendered. If you happen to be a necromancer perhaps we could work out a deal for the armor.

**You say:** `necromancer`



>**Bella Stremi says:** I have a cap, robes, sleeves, pants, shawl, bracer, and sandals for a necromancer. Frantip has the rest just ask him about armor and I'm sure he'll help you. Which are you interested in?

**You say:** `cap`



>**Bella Stremi says:** For the cap of pestilence you'll have to bring me a sky jewel, an aged gold coin, a dark gem, and a priceless book.

**You say:** `robe`



>**Bella Stremi says:** For the robe of pestilence you'll have to bring me a meteor jewel, a miniature armband, a mark of fortune, and a sun wraith eye.

**You say:** `sleeves`



>**Bella Stremi says:** For the sleeves of pestilence you'll have to bring me an astral jewel, a petrified totem, a frozen hailstone, and a glowing crystal.

**You say:** `pants`



>**Bella Stremi says:** For the pants of pestilence you'll have to bring me a sun jewel, a divining rod, an aged platinum symbol, and a silver sign.

**You say:** `shawl`



>**Bella Stremi says:** For the shawl of pestilence you'll have to bring me a moon jewel an ancient fossil, and some wrought iron shavings.

**You say:** `bracer`



>**Bella Stremi says:** For the bracer of pestilence you'll have to bring me a star jewel, a granite idol, and an ancient silver coin.

**You say:** `sandals`



>**Bella Stremi says:** For the sandals of pestilence you'll have to bring me a cloud jewel, a blackened ornament, and a snake scale sceptre.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/4741" data-url="4741" class="tooltip-link link">Aged Gold Coin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_965.png" alt="" /> <a
                                href="/item/4742" data-url="4742" class="tooltip-link link">Dark Gem</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/4743" data-url="4743" class="tooltip-link link">Priceless Book</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/3723" data-url="3723" class="tooltip-link link">Cap of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_509.png" alt="" /> <a
                                href="/item/4744" data-url="4744" class="tooltip-link link">Miniature Armband</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4745" data-url="4745" class="tooltip-link link">Mark of Fortune</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1130.png" alt="" /> <a
                                href="/item/4746" data-url="4746" class="tooltip-link link">Sun Wraith Eye</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1126.png" alt="" /> <a
                                href="/item/3724" data-url="3724" class="tooltip-link link">Robe of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/4748" data-url="4748" class="tooltip-link link">Petrified Totem</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/4749" data-url="4749" class="tooltip-link link">Frozen Hailstone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/4750" data-url="4750" class="tooltip-link link">Glowing Crystal</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_670.png" alt="" /> <a
                                href="/item/3725" data-url="3725" class="tooltip-link link">Sleeves of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/4751" data-url="4751" class="tooltip-link link">Divining Rod</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/4752" data-url="4752" class="tooltip-link link">Aged Platinum Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/4753" data-url="4753" class="tooltip-link link">Silver Sign</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_631.png" alt="" /> <a
                                href="/item/3726" data-url="3726" class="tooltip-link link">Pants of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_804.png" alt="" /> <a
                                href="/item/4771" data-url="4771" class="tooltip-link link">Ancient Fossil</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1032.png" alt="" /> <a
                                href="/item/4772" data-url="4772" class="tooltip-link link">Wrought Iron Shavings</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/3727" data-url="3727" class="tooltip-link link">Shawl of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/4773" data-url="4773" class="tooltip-link link">Granite Idol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/4774" data-url="4774" class="tooltip-link link">Ancient Silver Coin</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_638.png" alt="" /> <a
                                href="/item/3728" data-url="3728" class="tooltip-link link">Bracer of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_767.png" alt="" /> <a
                                href="/item/4775" data-url="4775" class="tooltip-link link">Blackened Ornament</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_821.png" alt="" /> <a
                                href="/item/4776" data-url="4776" class="tooltip-link link">Snake Scale Sceptre</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_558.png" alt="" /> <a
                                href="/item/3729" data-url="3729" class="tooltip-link link">Sandals of Pestilence</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Bella Stremi says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)