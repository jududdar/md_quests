# Priestess Ghalea



[Priestess Ghalea](/npc/67024) is a level 61 Dwarf GM Cleric that spawns in [North Kaladim](/zone/67).



## Dialog

**You say:** `hail`



>**Priestess Ghalea says:** Welcome to the Church of Underfoot. Please open your soul to the greatness of Brell Serilis. May he guide you in all your future eavors. And may your soles long for the [Soil of Underfoot].

**You say:** `soil`



if **Faction** >= Kindly then 



>**Priestess Ghalea says:** I can trust you with the soil of Underfoot, but first you must obtain four portions of fairy dust. Return them to me and I shall mix it and pray over it. Then I shall give you a pouch of soil of Underfoot.




else



>**Priestess Ghalea says:** The Clerics of Underfoot have yet to see your faith directed towards our wills. Perhaps you should assist Master Gunlok Jure in the crusade against the undead.


**You say:** `candle`



>**Priestess Ghalea says:** The Candle of Bravery is used for temple ceremonies here in Kaladim. When the candle burns out, I must venture to the frigid village of Halas far to the north of the continent of Antonica. There I will take the candlestick and the [soil of Underfoot] to Dok. He must create the candle in the very ornate candlestick.
end



## Turn-Ins



local text = "I will need four portions of fairy dust to create the soil of Underfoot.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18765" data-url="18765" class="tooltip-link link">Dirt Covered Letter</a>) then


>**Priestess Ghalea says:** Welcome to the Underfoot Cathedral. I am High Priestess Ghalea. Here is your guild tunic. Now. let's get you started helping us spread the will of Brell.


Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+100</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+100</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+75</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13514" data-url="13514" class="tooltip-link link">Dusty Tunic*</a> (+20 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/12106" data-url="12106" class="tooltip-link link">Fairy Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/12106" data-url="12106" class="tooltip-link link">Fairy Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/12106" data-url="12106" class="tooltip-link link">Fairy Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/12106" data-url="12106" class="tooltip-link link">Fairy Dust</a>) then  


>**Priestess Ghalea says:** May the mighty power of Brell saturate this soil with his divinity.  Here you are, my noble friend.  You may have a pouch of the soil of Underfoot.





Your faction standing with [Clerics of Underfoot](/faction/227) got better (<span class='text-success'>+5</span>)


Your faction standing with [Kazon Stormhammer](/faction/274) got better (<span class='text-success'>+5</span>)


Your faction standing with [Miners Guild 249](/faction/293) got better (<span class='text-success'>+3</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/12282" data-url="12282" class="tooltip-link link">Soil of Underfoot</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**
