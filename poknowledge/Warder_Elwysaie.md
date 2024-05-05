# Warder Elwysaie



[Warder Elwysaie](/npc/202007) is a level 61 Wood Elf GM Ranger that spawns in [Plane of Knowledge](/zone/202).





## Dialog

**You say:** `Hail`



if(e.other:Race() == "Dark Elf" or e.other:Race() == "Iksar" or e.other:Race() == "Troll" or e.other:Race() == "Ogre" or e.other:Class() == "Shadowknight" or e.other:Class() == "Necromancer") then



e.self:DoAnim(48);



e.self:Emote("stands tall, eyeing Soandso before her with neither disdain nor favor as she delivers a proper nod of greetings. 'Greetings to you, dark one. You stand within the district of Tanaan 


else



e.self:DoAnim(70);



>*Warder Elwysaie gives a formal bow at the waist in an almost regal greeting toward Soandso. 'Good day to you , traveler, and may Tunare's gracious hand guide your fate with freedom.  I am Warder Elwysaie, a soldier and guardian of nature in my life upon Norrath. Here, I am a soldier still but one of faith and knowledge. I set my blades down long ago, and though I understand most gravely that the shadow of corruption that threatens this delicate and necessary balance still looms most deadly over us, I was no longer able to be nature's wrath adn vengeance. It was then that I heard the calling of New Tanaan and eagerly I followed to this place of neutrality. In the recent times where Norrath's travelers who have yet to appeal to the Plane of Knowledge grace us as visitors and students of our ways, I have volunteered my former status and knowledge to any young ranger who may need guidance in their skills as they grow in power.*

end



## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_746.png" alt="" /> <a
                                href="/item/4891" data-url="4891" class="tooltip-link link">Thorny Vine Helm</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_624.png" alt="" /> <a
                                href="/item/4892" data-url="4892" class="tooltip-link link">Thorny Vine Chestplate</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_622.png" alt="" /> <a
                                href="/item/4893" data-url="4893" class="tooltip-link link">Thorny Vine Vambraces</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_516.png" alt="" /> <a
                                href="/item/4894" data-url="4894" class="tooltip-link link">Thorny Vine Bracer</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_531.png" alt="" /> <a
                                href="/item/4895" data-url="4895" class="tooltip-link link">Thorny Vine Gauntlets</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_540.png" alt="" /> <a
                                href="/item/4896" data-url="4896" class="tooltip-link link">Thorny Vine Greaves</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_524.png" alt="" /> <a
                                href="/item/4897" data-url="4897" class="tooltip-link link">Thorny Vine Boots</a>}

if(count > 0) then


repeat



>**Warder Elwysaie says:** Thank you, Soandso.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
