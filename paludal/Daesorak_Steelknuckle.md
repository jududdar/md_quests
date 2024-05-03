# Daesorak Steelknuckle




## Dialog

**You say:** `hail`



>**Daesorak Steelknuckle says:** Lo there stranger what ya doin in ere? You know how dangerous it can be down ere! I be lucky I got some of da finest miners werkin for me. I sure do hope we get those supplies soon.

**You say:** `supplies`



>**Daesorak Steelknuckle says:** Well da usual supplies dat ya need to keep a mining operation like this one goin smoothly. Mostly newer tools since ours be all rusted an worn from our hard work. If ye are interested in helpin us out ye could go talk to Coglirax in da Shadowhaven. We call em Ol Coggo, Im sure he would be able to give ye some goods to deliver ere.

**You say:** `retrieve the mining pick`



>**Daesorak Steelknuckle says:** Excellent, Soandso. Please go see Terasol in Katta to retrieve my mining supplies. Bring him this note to show that you were sent by me. And dunt stray off track with these supplies, we needs em bad!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_869.png" alt="" /> <a
                                href="/item/4754" data-url="4754" class="tooltip-link link">A Jarbled Note</a>

**You say:** `return a letter`



>**Daesorak Steelknuckle says:** I thank you, Soandso. Without your help I doubt we would have been able to finish this project on time! Please take this to my wife Aliane back home. You can surely count on me telling the Patriarch of how much help you have been when I return home. I wish you good journeys as for me its back to work I go!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/4756" data-url="4756" class="tooltip-link link">Letter to Aliane</a>
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_539.png" alt="" /> <a
                                href="/item/4747" data-url="4747" class="tooltip-link link">Bag of Rations</a>) then


>**Daesorak Steelknuckle says:** Ah these must be from ol Coggo! Ye see I had sent out a few men to gather some new picks an such for the mining operation ere but they haven't returned yet. I'm really in need of some picks that are being held in Katta by a friend of mine. Will you [retrieve the mining picks] for me?


Your faction standing with [House of Stout](/faction/1512) got better (<span class='text-success'>+5</span>)


Your faction standing with [Traders of the Haven](/faction/1508) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+5000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_978.png" alt="" /> <a
                                href="/item/4755" data-url="4755" class="tooltip-link link">A Bundle of Mining Picks</a>) then


>**Daesorak Steelknuckle says:** Ye did it, Soandso! Ye hear dat, boys? Dis outlander ere jess delivered us our new minin picks! You have no idea how much these supplies will aid our operation! As a final task would you be able to [return a letter] to me wife back home?


Your faction standing with [House of Stout](/faction/1512) got better (<span class='text-success'>+5</span>)


Your faction standing with [Traders of the Haven](/faction/1508) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+5000 exp)

 


yippee(e);

**This NPC *should* return incorrect items given.**

function yippee(e)

eq.get_entity_list():GetMobByNpcTypeID(156064):Say("Hurray!");

eq.get_entity_list():GetMobByNpcTypeID(156061):Say("Hurray!");

eq.get_entity_list():GetMobByNpcTypeID(156065):Say("Hurray!");

eq.get_entity_list():GetMobByNpcTypeID(156066):Say("Hurray!");

eq.get_entity_list():GetMobByNpcTypeID(156064):CastToMob():DoAnim(8);

eq.get_entity_list():GetMobByNpcTypeID(156061):CastToMob():DoAnim(8);

eq.get_entity_list():GetMobByNpcTypeID(156065):CastToMob():DoAnim(8);

eq.get_entity_list():GetMobByNpcTypeID(156066):CastToMob():DoAnim(8);