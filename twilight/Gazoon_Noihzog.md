# Gazoon Noihzog
## Dialog

**You say:** `hail`



>*Gazoon Noihzog gasps in astonishment. 'Who do you think you are coming to my island?  I didn't invite you!*

**You say:** `island`



>**Gazoon Noihzog says:** It's my island and no one else's! This is where I hang out to blow stuff up, well that and they kicked me out of Katta.

**You say:** `blow stuff`



>**Gazoon Noihzog says:** Yeah that's what I usually do here.  Why so interested, are ya a fellow wizard?

**You say:** `wizard`



>**Gazoon Noihzog says:** Oh boy do I have something that you want. A nice set of wizardly armor that you can really waggle yer fingers in.

**You say:** `armor`



>**Gazoon Noihzog says:** It's not free that's for sure. If you want the armor I have the cap, robe, sleeves, pants, shawl, bracer and sandals. My buddy Trizpo has the rest you should go ask him about the armor.

**You say:** `bracer`



>**Gazoon Noihzog says:** For the bracer you'll have to fetch me a cloud jewel, a mark of potency, and book of applied magic.

**You say:** `cap`



>**Gazoon Noihzog says:** For the cap you'll have to fetch me a meteor jewel, some explosive dust, a mark of explosion, and a book of wizardry.

**You say:** `pants`



>**Gazoon Noihzog says:** For the pants you'll have to fetch me a moon jewel, a mark of energy, a gilded branch and some fiery sand.

**You say:** `robe`



>**Gazoon Noihzog says:** For the robe you'll have to fetch me an astral jewel, a mark of sorcery, a book of sorcery, and a globe of power.

**You say:** `sandals`



>**Gazoon Noihzog says:** For the sandals you'll have to fetch me a sky jewel, a mark of intensity, and a sun stained steel rod.

**You say:** `shawl`



>**Gazoon Noihzog says:** For the shawl you'll have to fetch me a star jewel, a mark of force, and some tro jeg toes.

**You say:** `sleeves`



>**Gazoon Noihzog says:** For the sleeves you'll have to fetch me a sun jewel, a mark of implosion, some grub worm guts, and a fiery heart.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/4724" data-url="4724" class="tooltip-link link">Book of Applied Magic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4723" data-url="4723" class="tooltip-link link">Mark of Potency</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_638.png" alt="" /> <a
                                href="/item/3715" data-url="3715" class="tooltip-link link">Bracer of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/4711" data-url="4711" class="tooltip-link link">Book of Wizardry</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1076.png" alt="" /> <a
                                href="/item/4709" data-url="4709" class="tooltip-link link">Explosive Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4710" data-url="4710" class="tooltip-link link">Mark of Explosion</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_639.png" alt="" /> <a
                                href="/item/3710" data-url="3710" class="tooltip-link link">Cap of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1076.png" alt="" /> <a
                                href="/item/4720" data-url="4720" class="tooltip-link link">Fiery Sand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_978.png" alt="" /> <a
                                href="/item/4719" data-url="4719" class="tooltip-link link">Gilded Branch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4718" data-url="4718" class="tooltip-link link">Mark of Energy</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_631.png" alt="" /> <a
                                href="/item/3713" data-url="3713" class="tooltip-link link">Pants of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/4713" data-url="4713" class="tooltip-link link">Book of Sorcery</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/4714" data-url="4714" class="tooltip-link link">Globe of Power</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4712" data-url="4712" class="tooltip-link link">Mark of Sorcery</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_838.png" alt="" /> <a
                                href="/item/3711" data-url="3711" class="tooltip-link link">Robe of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4725" data-url="4725" class="tooltip-link link">Mark of Intensity</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_732.png" alt="" /> <a
                                href="/item/4726" data-url="4726" class="tooltip-link link">Sun Stained Steel Rod</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_558.png" alt="" /> <a
                                href="/item/3716" data-url="3716" class="tooltip-link link">Sandals of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4721" data-url="4721" class="tooltip-link link">Mark of Force</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1094.png" alt="" /> <a
                                href="/item/4722" data-url="4722" class="tooltip-link link">Tro Jeg Toes</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_665.png" alt="" /> <a
                                href="/item/3714" data-url="3714" class="tooltip-link link">Shawl of Detonation</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/4717" data-url="4717" class="tooltip-link link">Fiery Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_926.png" alt="" /> <a
                                href="/item/4716" data-url="4716" class="tooltip-link link">Grub Worm Guts</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/4715" data-url="4715" class="tooltip-link link">Mark of Implosion</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_670.png" alt="" /> <a
                                href="/item/3712" data-url="3712" class="tooltip-link link">Sleeves of Detonation</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Gazoon Noihzog says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)