# Brolan Geppal



[Brolan Geppal](/npc/170051) is a level 40 Half Elf Bard that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>**Brolan Geppal says:** Well met friend, lovely day isn't it?

**You say:** `armor`



>**Brolan Geppal says:** Yes Shelia told me I may have some people asking me about the armor I have. Are ya a bard?

**You say:** `bard`



>**Brolan Geppal says:** Good, I have a [mask], [cloak], [gauntlets], [gorget], [girdle], and a [sword].

**You say:** `cloak`



>**Brolan Geppal says:** For the cloak you must gather these things. An Astral jewel, a mark of melody, an onyx studded medal, and a porous rock.

**You say:** `gauntlets`



>**Brolan Geppal says:** For the gauntlets you must gather these things. A sun jewel, a mark of anthems, and a fire emerald studded medal.

**You say:** `girdle`



>**Brolan Geppal says:** For the girdle you must gather these things. A star jewel, a mark of composition, a peridot studded medal, and a seared brand.

**You say:** `gorget`



>**Brolan Geppal says:** For the gorget you must gather these things a moon jewel, a mark of psalms, and a black pearl studded medal.

**You say:** `mask`



>**Brolan Geppal says:** For the mask you must gather these things a meteor jewel, a mark of tenor, and a star sapphire studded medal.

**You say:** `sword`



>**Brolan Geppal says:** For the sword you must gather these things a cloud jewel, a mark of chants, a red stone idol, and a moonstone studded medal.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5393" data-url="5393" class="tooltip-link link">Mark of Melody</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5394" data-url="5394" class="tooltip-link link">Onyx Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/5395" data-url="5395" class="tooltip-link link">Porous Rock</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_663.png" alt="" /> <a
                                href="/item/3928" data-url="3928" class="tooltip-link link">Bravado's Cape</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5397" data-url="5397" class="tooltip-link link">Fire Emerald Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5396" data-url="5396" class="tooltip-link link">Mark of Anthems</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/3929" data-url="3929" class="tooltip-link link">Bravado's Gauntlets</a> (+25000 exp)

 
  
elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5474" data-url="5474" class="tooltip-link link">Mark of Composition</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5475" data-url="5475" class="tooltip-link link">Peridot Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/5476" data-url="5476" class="tooltip-link link">Seared Brand</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_549.png" alt="" /> <a
                                href="/item/3931" data-url="3931" class="tooltip-link link">Bravado's Girdle</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5399" data-url="5399" class="tooltip-link link">Black Pearl Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5398" data-url="5398" class="tooltip-link link">Mark of Psalms</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_626.png" alt="" /> <a
                                href="/item/3930" data-url="3930" class="tooltip-link link">Bravado's Gorget</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5349" data-url="5349" class="tooltip-link link">Mark of Tenor</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5354" data-url="5354" class="tooltip-link link">Star Sapphire Studded Medal</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_772.png" alt="" /> <a
                                href="/item/3910" data-url="3910" class="tooltip-link link">Bravado's Mask</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5477" data-url="5477" class="tooltip-link link">Mark of Chants</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/5479" data-url="5479" class="tooltip-link link">Moonstone Studded Medal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/5478" data-url="5478" class="tooltip-link link">Red Stone Idol</a>) then


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_590.png" alt="" /> <a
                                href="/item/3932" data-url="3932" class="tooltip-link link">Bravado's Blade</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Brolan Geppal says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)