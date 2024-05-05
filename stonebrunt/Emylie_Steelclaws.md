# Emylie Steelclaws



[Emylie Steelclaws](/npc/100195) is a level 22 Kerran Monk that spawns in [Stonebrunt Mountains](/zone/100).



## Dialog

**You say:** `hail`



if **Faction** >= Dubious +300 then



>**Emylie Steelclaws says:** Shalom friend. My mate Kalaaro is the primary blacksmith of our village. I mostly create his tools, do touch ups and refurbishes, and maintain the [kejek forge].


else



>**Emylie Steelclaws says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `kejek forge`



if **Faction** >= Dubious +300 then



>**Emylie Steelclaws says:** Our forge has received the blessings of the Titan Spirits to burn with a supernatural flame! This flame has many beneficial properties but most importantly it can aid in freeing the spirits that have been imprisoned in materials by evil sorcerers.


else



>**Emylie Steelclaws says:** You have done much to anger the spirits thus you are not accepted by our people.


**You say:** `purification process`



if **Faction** >= Dubious +300 then



>**Emylie Steelclaws says:** The crystalline shadow must be purified in the kejek forge using a special hammer blessed by the Titan Spirits. I will craft a hammer for you to take to the Titans for their blessings if you bring me a Large Brick of High Quality Ore and an Oak Shaft. Once the hammer is blessed you may use it in the kejek forge to purify the crystalline shadow and transfer the spirits contained within it to a Soul Orb that must be taken to our village seer.


else



>**Emylie Steelclaws says:** You have done much to anger the spirits thus you are not accepted by our people.

end



## Turn-Ins





if **Faction** >= Dubious +300 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1138.png" alt="" /> <a
                                href="/item/10469" data-url="10469" class="tooltip-link link">Large Brick of High Quality Ore</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_601.png" alt="" /> <a
                                href="/item/10456" data-url="10456" class="tooltip-link link">Oak Shaft</a>) then 


>*Emylie Steelclaws takes the supplies and begins to work on the hammer. She works swiftly and efficiently then cools the finished hammer and hands it to you.*


Your faction standing with [Kejek Village](/faction/5011) got better (<span class='text-success'>+2</span>)


Your faction standing with [Peace Keepers](/faction/298) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_567.png" alt="" /> <a
                                href="/item/6981" data-url="6981" class="tooltip-link link">Kejekan Smithy Hammer</a> (+5000 exp)

 

**This NPC *should* return incorrect items given.**
