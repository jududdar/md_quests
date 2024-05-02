# Brutol Rhaksen
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Brutol Rhaksen says:** Oh, hello down there, puny one. I'm Brutol Rhaksen. Commmander of warriors who [serve] the Dismal Rage, and that's really all you need to know..for now.


**You say:** `serve`




>**Brutol Rhaksen says:** You must become strong to survive amongst the ranks of the Dismal Rage. Take this note to Rolfic Gohar and he will help you get a suit of armor to protect your scrawny hide from the weapons of our enemies. Once you have been properly outfitted return to me and will give you your [next orders].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_868.png" alt="" /> <a
                                href="/item/19843" data-url="19843" class="tooltip-link link">Note to Rolfic Gohar</a>


**You say:** `next orders`




>**Brutol Rhaksen says:** Ready to make yourself useful Soandso ? Beneath West Freeport are sewer tunnels leading to North Freeport being used by the Knights of Truth and the Sentries and Passion that have gained too much notoriety with the Freeport Militia and the Dismal Rage to pass safely through the eastern and western quarters of Freeport. We believe a sympathizer of the Sentries of Passion, Tarsa Yovar, is hiding somewhere in the western tunnel system. The sympathizer is a Steel Warrior faithful to Erollisi and although she is only a minor nuisance must be dealt with. Find her and bring me her head.

end


## Turn-Ins



local expansion_flag = eq.get_current_expansion();



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18857" data-url="18857" class="tooltip-link link">A tattered note</a>) then 


>**Brutol Rhaksen says:** Hahaha.. I sure hope you prove more valuable than you look, little one.


Your faction standing with [Dismal Rage](/faction/271) got better (<span class='text-success'>+100</span>)


Your faction standing with [Knights of Truth](/faction/281) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Opal Darkbriar](/faction/296) got better (<span class='text-success'>+20</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13561" data-url="13561" class="tooltip-link link">Faded Crimson Tunic*</a> (+20 exp)

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_983.png" alt="" /> <a
                                href="/item/19932" data-url="19932" class="tooltip-link link">Tarsa Yovar's Head</a>) then 


>**Brutol Rhaksen says:** Take this and get it sharpened. Bring it back to me with a Giant Rattlesnake Skin and you will have proven yourself able to wield a Dismal Rage Battle Axe, to help teach the way of Innoruuk!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/19921" data-url="19921" class="tooltip-link link">Dull Dismal Battleaxe</a> (+100 exp)

 

elseif(expansion_flag >= 4.0 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/19926" data-url="19926" class="tooltip-link link">Sharpened Dismal Battleaxe</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_813.png" alt="" /> <a
                                href="/item/19852" data-url="19852" class="tooltip-link link">Giant Rattlesnake Skin</a>) then 


>**Brutol Rhaksen says:** You have proven your faith Soandso. Take this to vanquish any and all whom question the absolute power of Innoruuk!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_568.png" alt="" /> <a
                                href="/item/19938" data-url="19938" class="tooltip-link link">Dismal Rage Battle Axe</a> (+100 exp)

 

**This NPC *should* return incorrect items given.**
;

