# Shrub Marwood



## Dialog

**You say:** `hail`



>*Shrub Marwood brushes pollen off of his tunic. 'Aachoo!! Oh!! Hello. Please look around. Unless you are a [druid looking for work].'*


e.self:DoAnim(55);

**You say:** `druid looking for work`



>**Shrub Marwood says:** Good. I need a stout adventurer to go to the wilds and find me a few items. I need some tump stumps - one Kromdul and one Kromdek type. I also need a mantrap root. Get me those three things and I will give you this handy shillelagh I found in the forest.


e.self:DoAnim(48);

**You say:** `fertile crop`



>**Shrub Marwood says:** Looking to get hold of my family druid spell, ehh? It doesn't come without a price. Lucky for you all I need is for you to run a small errand for me. Go fetch me a Sarnak farsight crystal, some Sarnak nightdust, some strathebone heal silk and some powder of Tsu. Do that and I will give you a copy of my family secret.


e.self:DoAnim(60);
end



## Turn-Ins



local text1 = "Hey!! Trying to pull a fast one?!! I said I wanted tump stumps of Kromdek and Kromdul type and a mantrap root!!";



local text2 = "If you want the [Fertile Crop] druid spell, I must insist that you complete your small task.";



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_583.png" alt="" /> <a
                                href="/item/12960" data-url="12960" class="tooltip-link link">Mantrap Root</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_978.png" alt="" /> <a
                                href="/item/12955" data-url="12955" class="tooltip-link link">A Tump Stump</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_978.png" alt="" /> <a
                                href="/item/12958" data-url="12958" class="tooltip-link link">A Tump Stump</a>) then


>*Shrub Marwood tosses the mantrap root out the window.. SPLASH!! 'I made a mistake. I didn't need that one. Here is the shillelagh I told you about. I found it in some burned out woods far from here. I cleaned it up and found it had a spark of mana so I had it enchanted with a few charges of my spell, [Fertile Crop]. Hope you like it.'*


Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+5</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+3</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+3</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_602.png" alt="" /> <a
                                href="/item/12953" data-url="12953" class="tooltip-link link">Dark Oak Shillelagh</a> (+25000 exp)

 

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/11579" data-url="11579" class="tooltip-link link">A Farsight Crystal</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_582.png" alt="" /> <a
                                href="/item/12753" data-url="12753" class="tooltip-link link">Pouch of Dust</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_782.png" alt="" /> <a
                                href="/item/12957" data-url="12957" class="tooltip-link link">Strathbone Silk</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1075.png" alt="" /> <a
                                href="/item/12959" data-url="12959" class="tooltip-link link">Shaman Powder</a>) then


>**Shrub Marwood says:** Great work! I wish I had the coin to hire you on permanently. Maybe I will, when I find the lost trade city of Torsis. Here is the spell I copied for you. Careful, the ink is still drying.


Your faction standing with [Inhabitants of Firiona Vie](/faction/248) got better (<span class='text-success'>+5</span>)


Your faction standing with [Emerald Warriors](/faction/326) got better (<span class='text-success'>+3</span>)


Your faction standing with [Storm Guard](/faction/312) got better (<span class='text-success'>+3</span>)


Your faction standing with [Legion of Cabilis](/faction/441) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Pirates of Gunthak](/faction/313) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/12954" data-url="12954" class="tooltip-link link">Fertile Crop</a> (+25000 exp)

 

**This NPC *should* return incorrect items given.**





