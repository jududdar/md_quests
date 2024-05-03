# Lendiniara the Keeper


## Dialog

if **Faction** >= Kindly then 


**You say:** `hail`




>**Lendiniara the Keeper says:** Greetings, Soandso. I am the keeper of relics. If you are brave I have tasks to test your might and perhaps rewards.


**You say:** `rewards`




>**Lendiniara the Keeper says:** One should ask of the tasks before worrying about rewards," .. e.other:Race() .. ".


**You say:** `tasks`




>**Lendiniara the Keeper says:** Enter into the halls of testing to complete these tasks. Seek out the ancient ones inside and see if your might is as great as theirs and fear not, those who you slay will be returned to the temple by the gift of Veeshan's great power. I have three tasks, which any may complete, as well as a request of both the arcane and the strong.


**You say:** `arcane`




>**Lendiniara the Keeper says:** Those who seek knowledge, will seek this task out for its reward is great. Three tears and a glowing orb will garner one an ancient mask. The White tear and the black tear for balance the runed tear to hold the balance and a glowing orb to return raw energy to the ancient mask.


**You say:** `strong`




>**Lendiniara the Keeper says:** Those who believe they are strong may be surprised after such a task. Seek out the cursed one and slay him, return to me when you have gathered a silver tear, a poison tear, a flame kissed tear and a serrated tear. End the cursed ones torment for a short time, before the high priest raises him to continue his suffering for eternity.


**You say:** `three`




>**Lendiniara the Keeper says:** Tears from the cursed you much seek for each task. The test of the Ruby Tear, the test of the Platinum Tear and the test of the Emerald Tear await all who wish to partake of them.


**You say:** `ruby tear`




>**Lendiniara the Keeper says:** The test of the ruby tear sounds simple enough, enter the halls of testing, secure a ruby tear, a white symbol, a silver symbol and a ruby symbol. I warn you mortal, those who walk the halls will rend your body and mind if you are not worthy.


**You say:** `platinum tear`




>**Lendiniara the Keeper says:** Seek the platinum tear and three symbols to bind its powers to a bracelet. The black symbol to add raw power, the serrated symbol to enchant its powers and the runed symbol to hold the powers to the bracelet.


**You say:** `emerald tear`




>**Lendiniara the Keeper says:** The emerald tear of Veeshan entrusted to the cursed one. Return this tear to me so I may return the powers of an ancient shield. Three symbols you must also seek. Emerald like the tear, one kissed by the flames of the elder wurms and one made of the ancient wyverns venomous poison.

 
elseif **Faction** >= Indifferent then


>**Lendiniara the Keeper says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Lendiniara the Keeper says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins





if **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31262" data-url="31262" class="tooltip-link link">Black Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31261" data-url="31261" class="tooltip-link link">White Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31263" data-url="31263" class="tooltip-link link">Runed Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/31260" data-url="31260" class="tooltip-link link">Glowing Drake Orb</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_772.png" alt="" /> <a
                                href="/item/31463" data-url="31463" class="tooltip-link link">Mask of the Silver Eyes</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31267" data-url="31267" class="tooltip-link link">Flame Kissed Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31266" data-url="31266" class="tooltip-link link">Poison Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31265" data-url="31265" class="tooltip-link link">Serrated Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31264" data-url="31264" class="tooltip-link link">Silver Tear</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_772.png" alt="" /> <a
                                href="/item/31464" data-url="31464" class="tooltip-link link">Silver Mask of the Slayer</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31259" data-url="31259" class="tooltip-link link">Ruby Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31270" data-url="31270" class="tooltip-link link">Ruby Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31253" data-url="31253" class="tooltip-link link">Silver Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31250" data-url="31250" class="tooltip-link link">White Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1056.png" alt="" /> <a
                                href="/item/31460" data-url="31460" class="tooltip-link link">Silver Charm of Tranquility</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31251" data-url="31251" class="tooltip-link link">Black Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31269" data-url="31269" class="tooltip-link link">Platinum Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31252" data-url="31252" class="tooltip-link link">Runed Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31254" data-url="31254" class="tooltip-link link">Serrated Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_521.png" alt="" /> <a
                                href="/item/31461" data-url="31461" class="tooltip-link link">Silver Bracelet of Speed</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31257" data-url="31257" class="tooltip-link link">Emerald Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31268" data-url="31268" class="tooltip-link link">Emerald Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31256" data-url="31256" class="tooltip-link link">Flame Kissed Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31255" data-url="31255" class="tooltip-link link">Poison Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_542.png" alt="" /> <a
                                href="/item/31462" data-url="31462" class="tooltip-link link">Buckler of Insight</a> (+20000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionHits(e)

>**Lendiniara the Keeper says:** You have done well, ".. e.other:Race() .. ". You have proven that you are strong, but do you dare enter those halls again?

Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+75</span>)

Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+18</span>)

Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-37</span>)