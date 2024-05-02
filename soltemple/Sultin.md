# Sultin


## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Sultin says:** I am Sultin - keeper of the three [Incandescent]s of power and the [Rod] of Insidious Glamour. If you are an Enchanter, perhaps we can deal.


**You say:** `incandescent`




>**Sultin says:** There are three Incandescent items of power - [Wand], [Mask] and [Gloves]. Are you [interested] in any of them?


**You say:** `interested.* wand`




>**Sultin says:** Ahh, the Incandescent Wand. If you will get the components to make another, I will give you mine. I will need a Pouch of Silver Dust, found on the dusty Werebat in the Estate of Unrest. I will also need a Silver wand, found on a Silvered Guard in the Temple of Cazic Thule. This wand will not be enchanted - you will need to pay Esmirella of the Northern Karana Gypsy Camp 50 gold to enchant it for you. When the Wand is fully enchanted, bring it and the pouch to me and I will give you the Incandescent Wand.


**You say:** `interested.* mask`




>**Sultin says:** An item of power - the Incandescent Mask. If you will bring me the components to make another, I will give you an Incandescent Mask. I will need a Glowing Mask, found on the skeletal monk in the caverns of Guk. I will also need all three Runes of Fortune. One Rune can be found on the Dark Elf Enynti in the Chasm below Castle Mistmoore. The other two can each be purchased for 50 golden coins each - one from Mizr N\`Mar in the Neriak City Library and the other from Madam Serena in the city of Qeynos. Bring me all three Runes and the Glowing Mask and I will give you your reward.


**You say:** `interested.* glove`




>**Sultin says:** My personal favorite - Incandescent Gloves. If you bring me the components to make another pair, I will give you my gloves. Incandescent Gloves are made by sewing together four other sets of gloves. Glowing Gloves can be found on our mortal enemies - the Shadowed Men. Radiant Gloves can be found on Radiant in the Feerrott. Enchanted and Gleaming gloves can be purchased for 50 golden coins from Tizina of the Lavastrom Gypsies and a bloodstone from Tarn Vislin of HighKeep. Bring me all four sets of gloves and I will give you a pair of Incadescent ones.


**You say:** `interested.* rod`




>**Sultin says:** If I am to give you this rod, you must bring me the parts to make another. I will need the Golden Rod from the froglok priest in Guk, as well as a Shining Stone from our mortal enemies, the Shadowed Men. Once you have obtained the Shining Stone, you will need to get it enchanted. Cynthia of the Rathe Mountain Gypsy Clan will enchant the Shining Stone for you - give it to her with 50 golden coins. When the Stone is fully enchanted, bring it and the rod to me and I will give you a Rod of Insidious Glamour.


**You say:** `what.* rod`




>**Sultin says:** I am keeper of the Rod of Insidious Glamour - a device of guile and deceit. The rod will increase the Charisma of whomever holds it. Are you [interested] in obtaining the [rod]?


else


**Sultin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins



local text = "Solusek Ro does not believe in half measures.";





if **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/10087" data-url="10087" class="tooltip-link link">Glowing Glamour Stone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_822.png" alt="" /> <a
                                href="/item/6337" data-url="6337" class="tooltip-link link">Golden Rod</a>) then


>**Sultin says:** Well done, adventurer. You have kept your part of the bargain, so I keep mine. Here is your rod.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_822.png" alt="" /> <a
                                href="/item/6329" data-url="6329" class="tooltip-link link">Rod of Insidious Glamour</a> (+1000 exp)

 




elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/12240" data-url="12240" class="tooltip-link link">Pouch of Silver Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/6340" data-url="6340" class="tooltip-link link">Glowing Silver Wand</a>) then


>**Sultin says:** I see that you are resourceful... you have earned your incandescent wand.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_810.png" alt="" /> <a
                                href="/item/6334" data-url="6334" class="tooltip-link link">Incandescent Wand</a> (+1000 exp)

 




elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2353" data-url="2353" class="tooltip-link link">Glowing Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2354" data-url="2354" class="tooltip-link link">Enchanted Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2355" data-url="2355" class="tooltip-link link">Gleaming Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2356" data-url="2356" class="tooltip-link link">Radiant Gloves</a>) then


>**Sultin says:** Four pairs of gloves you have given me ? I will give you one pair in return. We shall see who had the better deal.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2351" data-url="2351" class="tooltip-link link">Incandescent Gloves</a> (+1000 exp)

 




elseif **Faction** >= Indifferent and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2352" data-url="2352" class="tooltip-link link">Glowing Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10530" data-url="10530" class="tooltip-link link">Rune of Fortune</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10531" data-url="10531" class="tooltip-link link">Rune of Fortune</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/10532" data-url="10532" class="tooltip-link link">Rune of Fortune</a>) then


>**Sultin says:** Fortune favors you .. as will this mask.


Your faction standing with [Temple of Solusek Ro](/faction/415) got better (<span class='text-success'>+5</span>)


Your faction standing with [Shadowed Men](/faction/416) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2350" data-url="2350" class="tooltip-link link">Incandescent Mask</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
