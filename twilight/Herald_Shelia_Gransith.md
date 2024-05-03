# Herald Shelia Gransith


## Dialog

**You say:** `hail`



>**Herald Shelia Gransith says:** Welcome to the Twilight Sea!  This is the docking entrance to Katta Castellum. Soandso. Tell me do you know any songs?

**You say:** `songs`



>**Herald Shelia Gransith says:** Ah you do. You don't happen to be a bard do you?

**You say:** `bard`



>**Herald Shelia Gransith says:** Great. I have just what you need. Would you like to earn some armor?

**You say:** `armor`



>**Herald Shelia Gransith says:** I thought so I have a [helm], [breastplate], [vambraces], [greaves], [pauldrons], [bracer], and [boots]. For the rest speak to Brolan over there about armor.

**You say:** `breastplate`



>**Herald Shelia Gransith says:** For the breastplate you must bring me an astral jewel. a mark of music. a diamond studded medal. and a glorious flower.

**You say:** `vambraces`



>**Herald Shelia Gransith says:** For the vambraces you must bring me a sun jewel. a mark of entertainment. a sapphire studded medal. and velvet sleeves.

**You say:** `greaves`



>**Herald Shelia Gransith says:** For the greaves you must bring me a moon jewel. a mark of the drum. an emerald studded medal. and memory crystal.

**You say:** `pauldrons`



>**Herald Shelia Gransith says:** For the pauldrons you must bring me a star jewel. a mark of the mandolin. and an opal studded medal.

**You say:** `bracer`



>**Herald Shelia Gransith says:** For the bracer you must bring me a cloud jewel. a mark of song. and a pearl studded medal.

**You say:** `boots`



>**Herald Shelia Gransith says:** For the boots you must bring me a sky jewel. a mark of poetry. and a star ruby studded medal.

**You say:** `helm`



>**Herald Shelia Gransith says:** For the helm you must bring me a meteor jewel, a mark of rhythm, a ruby studded medal, and a fancy necklace.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5347" data-url="5347" class="tooltip-link link">Mark of Poetry</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5348" data-url="5348" class="tooltip-link link">Star Ruby Studded Medal</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_545.png" alt="" /> <a
                                href="/item/3909" data-url="3909" class="tooltip-link link">Bravado's Boots</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5346" data-url="5346" class="tooltip-link link">Pearl Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5345" data-url="5345" class="tooltip-link link">Mark of Song</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_671.png" alt="" /> <a
                                href="/item/3908" data-url="3908" class="tooltip-link link">Bravado's Bracer</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5335" data-url="5335" class="tooltip-link link">Diamond Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_721.png" alt="" /> <a
                                href="/item/5336" data-url="5336" class="tooltip-link link">Glorious Flower</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5334" data-url="5334" class="tooltip-link link">Mark of Music</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/3898" data-url="3898" class="tooltip-link link">Bravado's Breastplate</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5341" data-url="5341" class="tooltip-link link">Emerald Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5340" data-url="5340" class="tooltip-link link">Mark of the Drum</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/5342" data-url="5342" class="tooltip-link link">Memory Crystal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_611.png" alt="" /> <a
                                href="/item/3900" data-url="3900" class="tooltip-link link">Bravado's Greaves</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5343" data-url="5343" class="tooltip-link link">Mark of the Mandolin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5344" data-url="5344" class="tooltip-link link">Opal Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_798.png" alt="" /> <a
                                href="/item/3907" data-url="3907" class="tooltip-link link">Bravado's Pauldrons</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5337" data-url="5337" class="tooltip-link link">Mark of Entertainment</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5338" data-url="5338" class="tooltip-link link">Sapphire Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_669.png" alt="" /> <a
                                href="/item/5339" data-url="5339" class="tooltip-link link">Velvet Sleeves</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_546.png" alt="" /> <a
                                href="/item/3899" data-url="3899" class="tooltip-link link">Bravado's Vambraces</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_851.png" alt="" /> <a
                                href="/item/5330" data-url="5330" class="tooltip-link link">Fancy Necklace</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5328" data-url="5328" class="tooltip-link link">Mark of Rhythm</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5329" data-url="5329" class="tooltip-link link">Ruby Studded Medal</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_628.png" alt="" /> <a
                                href="/item/3897" data-url="3897" class="tooltip-link link">Bravado's Helm</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Herald Shelia Gransith says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)