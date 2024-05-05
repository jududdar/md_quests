# Brinaa Darkpact



[Brinaa Darkpact](/npc/93114) is a level 49 Dark Elf Cleric that spawns in [The Overthere](/zone/93).



## Dialog

**You say:** `Hail`



>**Brinaa Darkpact says:** Hello, Soandso. It's nice to see more able bodies around this part of the outland. We came here in search of the magical powers that are supposed to exist in the ruins and dungeons of this area. We need you to bring back evidence of this power in the form of scrolls. I can't offer much coin in payment, but I do have some rare scrolls I already brought back that may interest you, if you wish to [help in the search].

**You say:** `help in the search`



>**Brinaa Darkpact says:** Excellent! Here is what we are still seeking. The scrolls of Death Pact. Upheaval. Yaulp IV. and Reckoning. If you return one of these to me. I'll release one of my rare scrolls to you.
end



## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19203" data-url="19203" class="tooltip-link link">Spell: Death Pact</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19205" data-url="19205" class="tooltip-link link">Spell: Upheaval</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19209" data-url="19209" class="tooltip-link link">Spell: Yaulp IV</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19212" data-url="19212" class="tooltip-link link">Spell: Reckoning</a>}

if(count > 0) then


repeat



>**Brinaa Darkpact says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19210" data-url="19210" class="tooltip-link link">Spell: Unswerving Hammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19224" data-url="19224" class="tooltip-link link">Spell: Heroic Bond</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19420" data-url="19420" class="tooltip-link link">Spell: Sunskin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19206" data-url="19206" class="tooltip-link link">Spell: Word of Vigor</a>) (+1000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





