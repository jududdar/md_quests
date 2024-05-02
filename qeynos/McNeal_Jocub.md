# McNeal Jocub
## Dialog

**You say:** `hail`



>**McNeal Jocub says:** Good ta see ya! Now start showin' these poodlewalkers how a real fish drinks!

**You say:** `low`



>**McNeal Jocub says:** This is going to sound crazy, but my main supplier of [Blackburrow Stout] is one of the brewers themselves. I have run too low on the fine brew and need someone to [pick up my shipment].

**You say:** `pick up.* shipment`



>**McNeal Jocub says:** Take this note to the Qeynos Hills. Somewhere there, you shall find a gnoll at night called Gnasher. Give him the note. Now, get moving!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18800" data-url="18800" class="tooltip-link link">A tattered note</a>

**You say:** `blackburrow stout`



>**McNeal Jocub says:** Keep it down!! So you've heard of Blackburrow Stout? We sell it here in Fish's Backroom. If the Qeynos Guards knew, well.. it wouldn't be such a good thing. The stout is illegal, It's made by the gnolls. It is one of the finest brews you will ever taste. If you want any.. slide me a [moonstone].

**You say:** `moonstone`



>**McNeal Jocub says:** Looking for moonstones, are we? The only way I know of getting a moonstone is to hunt gnolls for Captain Tillin of the Qeynos Guards.
end

## Arrive at Waypoint Script

if(e.wp == 5) then


>**McNeal Jocub says:** Blast!! We are running [low]!!
end

## Signals

>**McNeal Jocub says:** You shall never take me alive!!

**McNeal Jocub attacks NPC:**  [Executioner](/npc/1202)
## Turn-Ins

local moonstone = 0;



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/13131" data-url="13131" class="tooltip-link link">Case of Blackburrow Stout</a>) then


>**McNeal Jocub says:** Good work, pal. Here's a little dough to spend, just don't spend it at any other bar.


Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+30</span>)


Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+7</span>)


Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+4</span>)


Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+9</span>)


 &#127873; **You receive:** None 

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 0 <img src='/static/icons/item_645.png' width='14' height='14'/> 1-5 <img src='/static/icons/item_646.png' width='14' height='14'/> 1-12 <img src='/static/icons/item_647.png' width='14' height='14'/> 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>) then


moonstone = 4;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>) then


moonstone = 3;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>) then


moonstone = 2;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10070" data-url="10070" class="tooltip-link link">Moonstone</a>) then


moonstone = 1;

if(moonstone > 0) then


repeat



>**McNeal Jocub says:** Here you go then. Don't go tellin' no Guards where that came from, I would hate to rid myself of a good paying customer.



Your faction standing with [Karana Residents](/faction/345) got better (<span class='text-success'>+1</span>)



Your faction standing with [Guards of Qeynos](/faction/262) got better (<span class='text-success'>+1</span>)



Your faction standing with [Priests of Life](/faction/341) got better (<span class='text-success'>+1</span>)



Your faction standing with [Knights of Thunder](/faction/280) got better (<span class='text-success'>+1</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_827.png" alt="" /> <a
                                href="/item/13107" data-url="13107" class="tooltip-link link">Black Burrow Stout</a> (+200 exp)

 



moonstone = moonstone - 1;


until moonstone == 0

**This NPC *should* return incorrect items given.**
