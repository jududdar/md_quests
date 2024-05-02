# Sir Morgan







## Arrive at Waypoint Script

if(e.wp == 1) then


>**Sir Morgan says:** Hello, Wimbley, old chap!

elseif(e.wp == 8) then


>**Sir Morgan says:** Almost there...

elseif(e.wp == 9) then


>**Sir Morgan says:** Well, here we are! It is just a short jaunt through the pass ahead. Just remember to take the high road. I'm off, then. Good luck!


e.self:SetRunning(true);

elseif(e.wp == 10) then


e.self:SetRunning(false);
end

## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then 



>**Sir Morgan says:** Hail, traveler!  Might I escort you through to Highpass? The path ahead is filled with giants and many other hungry beasts. I assure you, you will be safe with me. I must admit, I am quite experienced in the ways of the warrior. Do you [wish an escort] or will you [travel alone]?


else



>**Sir Morgan says:** No person in Karana would speak with you. You had best leave before my sword finds your skull!




**You say:** `escort`



if **Faction** >= Apprehensive then 



>**Sir Morgan says:** I shall be honored to escort you to Highpass, but you shall have to wait for a spell. I make trips every few hours. I also would be grateful to any who wish to donate gold coins to the upkeep of my armor. The rains in the plains cause much rusting.


else



>**Sir Morgan says:** No person in Karana would speak with you. You had best leave before my sword finds your skull!




**You say:** `travel alone`



if **Faction** >= Apprehensive then 



>**Sir Morgan says:** Then, good luck to you! May your faith protect you. Or at the very least, guide you to a grand afterlife.


else



>**Sir Morgan says:** No person in Karana would speak with you. You had best leave before my sword finds your skull!



end

## Turn-Ins




if **Faction** >= Apprehensive and  **You turn in:** gold = 5) then


>**Sir Morgan says:** What a grand donation!! You must be a rich noble to be making such a donation. Here, I am but a simple warrior, but I found this lying on the highway to Highpass Hold. The lifeless corpse next to it had no more need of it.


 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2041" data-url="2041" class="tooltip-link link">Mountain Lion Cape</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_564.png" alt="" /> <a
                                href="/item/2904" data-url="2904" class="tooltip-link link">Bear-hide Belt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_636.png" alt="" /> <a
                                href="/item/2312" data-url="2312" class="tooltip-link link">Ratskin Gloves</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_771.png" alt="" /> <a
                                href="/item/2307" data-url="2307" class="tooltip-link link">Snakeskin Mask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/8306" data-url="8306" class="tooltip-link link">Halfling Knife</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_544.png" alt="" /> <a
                                href="/item/10006" data-url="10006" class="tooltip-link link">Silver Earring</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/13944" data-url="13944" class="tooltip-link link">Highkeep Flask</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_728.png" alt="" /> <a
                                href="/item/13004" data-url="13004" class="tooltip-link link">Large Lantern</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_660.png" alt="" /> <a
                                href="/item/2106" data-url="2106" class="tooltip-link link">Patchwork Cloak</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_633.png" alt="" /> <a
                                href="/item/2112" data-url="2112" class="tooltip-link link">Patchwork Boots</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7007" data-url="7007" class="tooltip-link link">Rusty Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_736.png" alt="" /> <a
                                href="/item/5024" data-url="5024" class="tooltip-link link">Rusty Halberd</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_741.png" alt="" /> <a
                                href="/item/6015" data-url="6015" class="tooltip-link link">Rusty Flail</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_604.png" alt="" /> <a
                                href="/item/5021" data-url="5021" class="tooltip-link link">Rusty Scimitar</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_592.png" alt="" /> <a
                                href="/item/7012" data-url="7012" class="tooltip-link link">Bronze Dagger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/1331" data-url="1331" class="tooltip-link link">Damask Cap</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_561.png" alt="" /> <a
                                href="/item/17002" data-url="17002" class="tooltip-link link">Belt Pouch</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_831.png" alt="" /> <a
                                href="/item/13829" data-url="13829" class="tooltip-link link">Drom's Champagne</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_597.png" alt="" /> <a
                                href="/item/8011" data-url="8011" class="tooltip-link link">Hunting Bow</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15295" data-url="15295" class="tooltip-link link">Spell: Mircyl's Animation</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15324" data-url="15324" class="tooltip-link link">Spell: Shock of Blades</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15380" data-url="15380" class="tooltip-link link">Spell: Column of Frost</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15501" data-url="15501" class="tooltip-link link">Spell: Soothe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15051" data-url="15051" class="tooltip-link link">Spell: Glimpse</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_947.png" alt="" /> <a
                                href="/item/10019" data-url="10019" class="tooltip-link link">Bloodstone</a>) 

 






**This NPC *should* return incorrect items given.**

