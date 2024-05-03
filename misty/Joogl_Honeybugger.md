# Joogl Honeybugger


## Dialog

**You say:** `hail`



>**Joogl Honeybugger says:** Hello. I would shake your hand, but it would [hurt]. Ooooh! Owwy!

**You say:** `hurt`






>**Joogl Honeybugger says:** I was attacked by the bixies. They swarmed on me!! I think I got too near their queen. I need that honey to make a living! Get me a bandage and I will tell you where all their worker bee's buzz around.

**You say:** `I need the honeycomb`



>**Joogl Honeybugger says:** If you're looking for the honeycombs, I don't have any right now. I have been unable to get any since I was attacked by the little [buggers]. I will tell you where to get some if you will only get me a bandage for my bites.

**You say:** `what buggers`



>**Joogl Honeybugger says:** I was attacked by the bixies. They swarmed on me!! I think I got too near their queen. I need that honey to make a living! Get me a bandage and I will tell you where all their worker bees buzz around.
end



## Turn-Ins



local bandage = 0;



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>) then


bandage=4;

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>) then


bandage=3;

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>) then


bandage=2;

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_812.png" alt="" /> <a
                                href="/item/13009" data-url="13009" class="tooltip-link link">Bandages</a>) then


bandage=1;

if(bandage > 0) then


for i = 1, bandage do







>**Joogl Honeybugger says:** Oh thank you, Soandso. If you are ever going to gather bixie honeycomb's pray you do not run into the queen. The only way I know of collecting the honey is by intercepting the drone's and taking the honeycomb's they sometime's carry. Good luck!!







Your faction standing with [Merchants of Rivervale](/faction/292) got better (<span class='text-success'>+1</span>)



Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+1</span>)



Your faction standing with [Guardians of the Vale](/faction/263) got better (<span class='text-success'>+1</span>)



Your faction standing with [Mayor Gubbin](/faction/286) got better (<span class='text-success'>+1</span>)



Your faction standing with [Coalition of Tradefolk Underground](/faction/336) got worse (<span class='text-danger'>-1</span>)



**This NPC *should* return incorrect items given.**
