# Frist Furtun
## Dialog

**You say:** `hail`



>**Frist Furtun says:** Hail to thee, adventurer! I have been sent to this new land by the Clerics of Tunare in search of the new arcane magiks said to exist beyond this outpost. I myself once searched the nearby Outlands, but to go any further would lead to my certain death. Lately, the dangers have proven to be too much for adventurers and ones like myself. Have you also ventured to this land in search of these [new magiks?]

**You say:** `new magiks`



>**Frist Furtun says:** Ahh, wonderful! The more souls who search for these scrolls, the sooner I'll be able to return home and share this knowledge. The magiks are in the form of scrolls held by the strongest creatures of the Outlands. You will probably have the best luck searching in the darkest depths of the dungeons beyond this outpost. You might want to talk to the residents of this outpost for locations of these dreadful places. If you should happen to [have] any [duplicate scrolls], please come speak to me. I might be interested in working out a trade for a scroll you do not yet have.

**You say:** `duplicate scroll`



>**Frist Furtun says:** Great! The scrolls I am interested in are those of Death Pact, Upheaval, Yaulp IV, and Reckoning. If you bring me any one of these scrolls, I'll let you reach into my bag and pull out one of the four very rare scrolls that have come into my possession.
end

## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19203" data-url="19203" class="tooltip-link link">Spell: Death Pact</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19205" data-url="19205" class="tooltip-link link">Spell: Upheaval</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19209" data-url="19209" class="tooltip-link link">Spell: Yaulp IV</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19212" data-url="19212" class="tooltip-link link">Spell: Reckoning</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19233" data-url="19233" class="tooltip-link link">Spell: Upheaval</a>}

if(count > 0) then


repeat



>**Frist Furtun says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19210" data-url="19210" class="tooltip-link link">Spell: Unswerving Hammer</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19224" data-url="19224" class="tooltip-link link">Spell: Heroic Bond</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19420" data-url="19420" class="tooltip-link link">Spell: Sunskin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19206" data-url="19206" class="tooltip-link link">Spell: Word of Vigor</a>) (+1000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
