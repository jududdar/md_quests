# Trallen Grimhammer



[Trallen Grimhammer](/npc/170108) is a level 40 Dwarf Paladin that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>**Trallen Grimhammer says:** Greetings and well met Soandso. Don't listen to ol' Latrag over there he'll never stop brewin' the best durn ale to be found.

**You say:** `boots`



>**Trallen Grimhammer says:** For the boots yer gonna have to get me a sun jewel. a mark of destiny. and a fleshy vine.

**You say:** `armor`



>**Trallen Grimhammer says:** Latrag is goin' on 'bout his armor again isn't he. Well friend be ye a paladin?

**You say:** `paladin`



>**Trallen Grimhammer says:** Of course ya are Soandso. Why would have ya asked me about the armor if ye wasn't eh. I have the boots, mask, cloak, gauntlets, gorget, girdle, and a sword. Which do ye want?

**You say:** `mask`



>**Trallen Grimhammer says:** For the mask yer gonna have to get me a moon jewel, a mark of blessings, and some crystallized dew.

**You say:** `cloak`



>**Trallen Grimhammer says:** For the cloak yer gonna have to get me a star jewel, a mark of the steadfast, a lexicon of the sun, and some glade dew.

**You say:** `gauntlets`



>**Trallen Grimhammer says:** For the gauntlets yer gonna have to get me a cloud jewel, a mark of honor, and some naturally formed quartz.

**You say:** `gorget`



>**Trallen Grimhammer says:** For the gorget yer gonna have to get me a sky jewel, a mark of gallantry, and a lunar marked stone.

**You say:** `girdle`



>**Trallen Grimhammer says:** For the girdle yer gonna have to get me a meteor jewel, a mark of heart, a lexicon of the moon, and a dread leech eye.

**You say:** `sword`



>**Trallen Grimhammer says:** For the sword yer gonna have to get me an astral jewel, a mark of the noble, a hardened clay sculpture, and a runic ear plug.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5904" data-url="5904" class="tooltip-link link">Mark of Destiny</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_583.png" alt="" /> <a
                                href="/item/5905" data-url="5905" class="tooltip-link link">Fleshy Vine</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_545.png" alt="" /> <a
                                href="/item/3978" data-url="3978" class="tooltip-link link">Blessed Knight's Boots</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5908" data-url="5908" class="tooltip-link link">Mark of the Steadfast</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/5909" data-url="5909" class="tooltip-link link">Lexicon of the Sun</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1153.png" alt="" /> <a
                                href="/item/5910" data-url="5910" class="tooltip-link link">Glade Dew</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_663.png" alt="" /> <a
                                href="/item/3980" data-url="3980" class="tooltip-link link">Blessed Knight's Cloak</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4491" data-url="4491" class="tooltip-link link">Cloud Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5911" data-url="5911" class="tooltip-link link">Mark of Honor</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/5912" data-url="5912" class="tooltip-link link">Naturally Formed Quartz</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/3981" data-url="3981" class="tooltip-link link">Blessed Knight's Gauntlets</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5915" data-url="5915" class="tooltip-link link">Mark of Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/5916" data-url="5916" class="tooltip-link link">Lexicon of the Moon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_885.png" alt="" /> <a
                                href="/item/5917" data-url="5917" class="tooltip-link link">Dread Leech Eye</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_549.png" alt="" /> <a
                                href="/item/3983" data-url="3983" class="tooltip-link link">Blessed Knight's Girdle</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5913" data-url="5913" class="tooltip-link link">Mark of Gallantry</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/5914" data-url="5914" class="tooltip-link link">Lunar Marked Stone</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_626.png" alt="" /> <a
                                href="/item/3982" data-url="3982" class="tooltip-link link">Blessed Knight's Gorget</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5906" data-url="5906" class="tooltip-link link">Mark of Blessings</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/5907" data-url="5907" class="tooltip-link link">Crystallized Dew</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_772.png" alt="" /> <a
                                href="/item/3979" data-url="3979" class="tooltip-link link">Blessed Knight's Mask</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/5918" data-url="5918" class="tooltip-link link">Mark of the Noble</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/5919" data-url="5919" class="tooltip-link link">Hardened Clay Sculpture</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_756.png" alt="" /> <a
                                href="/item/5920" data-url="5920" class="tooltip-link link">Runic Ear Plug</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1171.png" alt="" /> <a
                                href="/item/3984" data-url="3984" class="tooltip-link link">Blessed Knight's Defender</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Trallen Grimhammer says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)