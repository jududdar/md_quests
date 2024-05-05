# Telkorenar



[Telkorenar](/npc/124104) is a level 66 Dragon Monk that spawns in [Temple of Veeshan](/zone/124).





## Dialog

if **Faction** >= Kindly then 


**You say:** `hail`




>**Telkorenar says:** The Strong seek me out, for one reason or another. It seems you have come here in peace. Perhaps you wish to prove yourself a mighty fighter? I respect only might, " .. e.other:Race() .. ".


**You say:** `prove`




>**Telkorenar says:** For the mighty I have four tests. The test of the tooth, the test of the flame, the test of the fire storm, and the test of protection. Which test do you wish to undertake?


**You say:** `tooth`




>**Telkorenar says:** With tooth and nail you must fight, deep into the halls of testing. Recover the white tear of power, the white symbol for purity, the silver symbol to calm ones self, and a glowing orb. If you can return these to me I will know you are a mighty fighter indeed.


**You say:** `flame`




>**Telkorenar says:** Return the black tear, the black symbol, the poison symbol, and the serrated symbol to me and you will have completed the test of flame. Your reward will be quite suitable to one who enters the fray of battle.


**You say:** `fire storm`




>**Telkorenar says:** Become like a fire storm and bring your wrath upon the inhabitants of the halls of testing. Return when you have the tear of poison and the serrated tear along with the a symbol kissed by flames and a ruby symbol.


**You say:** `protection`




>**Telkorenar says:** My fire will protect you if you are strong enough to endure this test. A ruby tear like my flames, an emerald tear like a forest ready to burn, an emerald symbol, and a platinum symbol are what I seek. With these I will forge pauldrons unlike any you have ever seen mortal. Go now and seek out what I desire.

 
elseif **Faction** >= Indifferent then


>**Telkorenar says:** You need to prove your dedication to our cause before I can discuss such matters with you.

else


**Telkorenar says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!
end



## Turn-Ins





if **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31257" data-url="31257" class="tooltip-link link">Emerald Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31268" data-url="31268" class="tooltip-link link">Emerald Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31270" data-url="31270" class="tooltip-link link">Ruby Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31258" data-url="31258" class="tooltip-link link">Platinum Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_769.png" alt="" /> <a
                                href="/item/31472" data-url="31472" class="tooltip-link link">Pauldrons of the Deep Flame</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/31260" data-url="31260" class="tooltip-link link">Glowing Drake Orb</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31253" data-url="31253" class="tooltip-link link">Silver Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31261" data-url="31261" class="tooltip-link link">White Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31250" data-url="31250" class="tooltip-link link">White Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_800.png" alt="" /> <a
                                href="/item/31469" data-url="31469" class="tooltip-link link">Serrated Dragon Tooth</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31262" data-url="31262" class="tooltip-link link">Black Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31251" data-url="31251" class="tooltip-link link">Black Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31255" data-url="31255" class="tooltip-link link">Poison Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31254" data-url="31254" class="tooltip-link link">Serrated Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_619.png" alt="" /> <a
                                href="/item/31470" data-url="31470" class="tooltip-link link">Earring of the Living Flame</a> (+20000 exp)

 

elseif **Faction** >= Kindly and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31256" data-url="31256" class="tooltip-link link">Flame Kissed Symbol</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31266" data-url="31266" class="tooltip-link link">Poison Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/31265" data-url="31265" class="tooltip-link link">Serrated Tear</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/31259" data-url="31259" class="tooltip-link link">Ruby Symbol</a>) then 


FactionHits(e);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_658.png" alt="" /> <a
                                href="/item/31471" data-url="31471" class="tooltip-link link">Cloak of the Fire Storm</a> (+20000 exp)

 

**This NPC *should* return incorrect items given.**

function FactionHits(e)

>**Telkorenar says:** You have done well, ".. e.other:Race() .. ". You have proven that you are strong, but do you dare enter those halls again?

Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+75</span>)

Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+18</span>)

Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-37</span>)