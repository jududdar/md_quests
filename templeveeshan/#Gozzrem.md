# Gozzrem


## Dialog

if **Faction** >= Kindly then 


**You say:** `hail`




>**Gozzrem says:** Greetings, Soandso. If you seek wisdom or the arcane I have tasks in the halls of testing you may complete to gain what you seek.


**You say:** `arcane`




>**Gozzrem says:** To garner a reward fit for one who walks the arcane path return to me the poison tear and the poison symbol. Along with these return the serrated symbol and the runed symbol. If this task is not hard enough for you, I have a second quest for you.


**You say:** `second`




>**Gozzrem says:** Tears may fall to the ground but not the ones you seek now. The black tear and the ruby tear you must seek. For more power I require the ruby symbol and a white symbol to bind the powers together. Upon the return of these four objects you will receive a wondrous reward.


**You say:** `wisdom`




>**Gozzrem says:** Wisdom can be gleaned from battle and that is what I wish you to do. Battle in the halls of testing may give you a different outlook on life. Which do you seek, the short battle or the long battle?


**You say:** `long`




>**Gozzrem says:** You will spend much time in the halls of testing. Seek out a runed tear and a flame kissed tear, bring them back to me with a symbol black as midnight and a glowing orb of the ancient drakes.


**You say:** `short`




>**Gozzrem says:** For the shortest time in the halls, seek out a Platinum tear held by the cursed one, a platinum symbol, a silver symbol and an emerald symbol as green as the forests. If you are able to return these to me I will reward you with a simple idol of the white dragons.

 
elseif **Faction** >= Indifferent then


>**Gozzrem says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Gozzrem says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end

## Turn-Ins





if **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31266" data-url="31266" class="tooltip-link link">Poison Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31255" data-url="31255" class="tooltip-link link">Poison Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31252" data-url="31252" class="tooltip-link link">Runed Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31254" data-url="31254" class="tooltip-link link">Serrated Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/31466" data-url="31466" class="tooltip-link link">White Dragon Statue</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31262" data-url="31262" class="tooltip-link link">Black Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31270" data-url="31270" class="tooltip-link link">Ruby Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31259" data-url="31259" class="tooltip-link link">Ruby Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31250" data-url="31250" class="tooltip-link link">White Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_525.png" alt="" /> <a
                                href="/item/31468" data-url="31468" class="tooltip-link link">Boots of Deep Thought</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31267" data-url="31267" class="tooltip-link link">Flame Kissed Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31263" data-url="31263" class="tooltip-link link">Runed Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31251" data-url="31251" class="tooltip-link link">Black Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/31260" data-url="31260" class="tooltip-link link">Glowing Drake Orb</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_764.png" alt="" /> <a
                                href="/item/31467" data-url="31467" class="tooltip-link link">Boots of Silent Striding</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31253" data-url="31253" class="tooltip-link link">Silver Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31258" data-url="31258" class="tooltip-link link">Platinum Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31257" data-url="31257" class="tooltip-link link">Emerald Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31269" data-url="31269" class="tooltip-link link">Platinum Tear</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/31465" data-url="31465" class="tooltip-link link">White Dragon Idol</a> (+20000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionHits(e)

>**Gozzrem says:** You have done well, ".. e.other:Race() .. ". You have proven that you are strong, but do you dare enter those halls again?

Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+75</span>)

Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+18</span>)

Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-37</span>)