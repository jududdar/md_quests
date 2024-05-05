# Pathfinder Viliken



[Pathfinder Viliken](/npc/202189) is a level 60 Wood Elf Shopkeeper that spawns in [Plane of Knowledge](/zone/202).




## Dialog

**You say:** `Hail`



>**Pathfinder Viliken says:** Greetings, friend, and welcome to New Tanaan. We have worked hard to properly greet you into our midst, and hope that our efforts shall not be in vain. As a ranger of Tunare in my former life upon Norrath, I have joined my fellow Pathfinders in scribing spells from memory of our journeys upon your world. These spells are not unique to the Plane of Knowledge, for they are the same as those Norrath offers to its guardians. However, they may be convenient for you to purchase here while you are browsing our libraries and engaging in the wonders of our beautiful, peaceful city. However, do not forget the scholars whilst you are engaging in the planes. You may stumble across a piece of pure arcane manifestation that may appear mundane at first, but with my help can become a spell of great power to all of nature's wardens.
end



## Turn-Ins



local ethereal =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_862.png" alt="" /> <a
                                href="/item/29112" data-url="29112" class="tooltip-link link">Ethereal Parchment</a>}

local spectral =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_683.png" alt="" /> <a
                                href="/item/29131" data-url="29131" class="tooltip-link link">Spectral Parchment</a>}

local glyphed =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_967.png" alt="" /> <a
                                href="/item/29132" data-url="29132" class="tooltip-link link">Glyphed Rune Word</a>}

if(ethereal > 0) then


repeat



e.self:Emote("takes the arcane item from you. Carefully, he inspects it 



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/26943" data-url="26943" class="tooltip-link link">Spell: Earthen Roots</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/21628" data-url="21628" class="tooltip-link link">Spell: Call of the Rathe</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/21627" data-url="21627" class="tooltip-link link">Spell: Strength of Tunare</a>) 

 



ethereal = ethereal - 1;


until ethereal == 0;

if(spectral > 0) then


repeat



e.self:Emote("takes the arcane item from you. Carefully, he inspects it 



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/26931" data-url="26931" class="tooltip-link link">Spell: Frozen Wind</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/26929" data-url="26929" class="tooltip-link link">Spell: Nature's Rebuke</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/26930" data-url="26930" class="tooltip-link link">Spell: Spirit of the Predator</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/21626" data-url="21626" class="tooltip-link link">Spell: Brushfire</a>) 

 



spectral = spectral - 1;


until spectral == 0;

if(glyphed > 0) then


repeat



e.self:Emote("takes the arcane item from you. Carefully, he inspects it 



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/21655" data-url="21655" class="tooltip-link link">Spell: Protection of the Wild</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/26932" data-url="26932" class="tooltip-link link">Spell: Cry of Thunder</a>) 

 



glyphed = glyphed - 1;


until glyphed == 0;

**This NPC *should* return incorrect items given.**





