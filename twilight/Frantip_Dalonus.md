# Frantip Dalonus



[Frantip Dalonus](/npc/170149) is a level 35 Human Shopkeeper that spawns in [Twilight](/zone/170).



## Dialog

**You say:** `hail`



>*Frantip Dalonus smiles briefly. 'Greetings to ye Soandso. If you be needin' the goods I've got 'em.*

**You say:** `armor`



>**Frantip Dalonus says:** Ah yes, I've been trying to get rid of this armor for some time. Do you happen to be a necromancer?

**You say:** `necromancer`



>**Frantip Dalonus says:** Very good! I have the veil, cloak, gloves, choker, belt, and staff. Which do you want?

**You say:** `veil`



>**Frantip Dalonus says:** For the veil of pestilence you will have to go retrieve for me a sky jewel, a jeweled rod, and a bronze brazier.

**You say:** `cloak`



>**Frantip Dalonus says:** For the cloak of pestilence you will have to go retrieve for me a meteor jewel, a hardened agate, a veiled lantern, and a white garnet.

**You say:** `gloves`



>**Frantip Dalonus says:** For the gloves of pestilence you will have to go retrieve for me an astral jewel, an antique lantern, and a glowing meteor fragment.

**You say:** `choker`



>**Frantip Dalonus says:** For the choker of pestilence you will have to go retrieve for me a sun jewel, an ancient relic of Tzon, and a fluorescent gem.

**You say:** `belt`



>**Frantip Dalonus says:** For the belt of pestilence you will have to go retrieve for me a moon jewel, an ancestral statuette, some dark hued wood, and an ocher gem.

**You say:** `staff`



>**Frantip Dalonus says:** For the staff of pestilence you will have to go retrieve for me a star jewel, some cultured spirits, some golden mushrooms, and a gem of awe.
end



## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4492" data-url="4492" class="tooltip-link link">Sky Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_822.png" alt="" /> <a
                                href="/item/4777" data-url="4777" class="tooltip-link link">Jeweled Rod</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1082.png" alt="" /> <a
                                href="/item/4778" data-url="4778" class="tooltip-link link">Bronze Brazier</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_677.png" alt="" /> <a
                                href="/item/3730" data-url="3730" class="tooltip-link link">Veil of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4493" data-url="4493" class="tooltip-link link">Meteor Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_955.png" alt="" /> <a
                                href="/item/4779" data-url="4779" class="tooltip-link link">Hardened Agate</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_728.png" alt="" /> <a
                                href="/item/4781" data-url="4781" class="tooltip-link link">Veiled Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/4782" data-url="4782" class="tooltip-link link">White Garnet</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_842.png" alt="" /> <a
                                href="/item/3731" data-url="3731" class="tooltip-link link">Cape of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4494" data-url="4494" class="tooltip-link link">Astral Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_729.png" alt="" /> <a
                                href="/item/4783" data-url="4783" class="tooltip-link link">Antique Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/4784" data-url="4784" class="tooltip-link link">Glowing Meteor Fragment</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_517.png" alt="" /> <a
                                href="/item/3732" data-url="3732" class="tooltip-link link">Gloves of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4488" data-url="4488" class="tooltip-link link">Sun Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1007.png" alt="" /> <a
                                href="/item/4785" data-url="4785" class="tooltip-link link">Ancient Relic of Tzon</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/4786" data-url="4786" class="tooltip-link link">Fluorescent Gem</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1046.png" alt="" /> <a
                                href="/item/3733" data-url="3733" class="tooltip-link link">Choker of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4489" data-url="4489" class="tooltip-link link">Moon Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_894.png" alt="" /> <a
                                href="/item/4787" data-url="4787" class="tooltip-link link">Ancestral Statuette</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_978.png" alt="" /> <a
                                href="/item/4788" data-url="4788" class="tooltip-link link">Dark Hued Wood</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_960.png" alt="" /> <a
                                href="/item/4789" data-url="4789" class="tooltip-link link">Ocher Gem</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_572.png" alt="" /> <a
                                href="/item/3734" data-url="3734" class="tooltip-link link">Belt of Pestilence</a> (+25000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/4490" data-url="4490" class="tooltip-link link">Star Jewel</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_586.png" alt="" /> <a
                                href="/item/4790" data-url="4790" class="tooltip-link link">Cultured Spirits</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1206.png" alt="" /> <a
                                href="/item/4791" data-url="4791" class="tooltip-link link">Golden Mushrooms</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_962.png" alt="" /> <a
                                href="/item/4792" data-url="4792" class="tooltip-link link">Gem of Awe</a>) then 


FactionReward(e)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/3735" data-url="3735" class="tooltip-link link">Staff of Pestilence</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Frantip Dalonus says:** Soandso take this and use it with pride.

Your faction standing with [Katta Castellum Citizens](/faction/1502) got better (<span class='text-success'>+5</span>)

Your faction standing with [Validus Custodus](/faction/1503) got better (<span class='text-success'>+1</span>)

Your faction standing with [Magus Conlegium](/faction/1504) got better (<span class='text-success'>+1</span>)

Your faction standing with [Citizens of Seru](/faction/1499) got worse (<span class='text-danger'>-2</span>)

Your faction standing with [Seru](/faction/1483) got worse (<span class='text-danger'>-1</span>)

Your faction standing with [Shoulders of Seru](/faction/1487) got worse (<span class='text-danger'>-1</span>)