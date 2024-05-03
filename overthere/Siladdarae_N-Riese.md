# Siladdarae N-Riese


## Dialog

**You say:** `Hail`



>**Siladdarae N-Riese says:** Hello, Soandso. This place is quite a formidable outpost, but it lacks the comforts of home. Once I have finished collecting some of my [missing scrolls], I'll be able to leave this place and all its hidden dangers.

**You say:** `missing scrolls`



>**Siladdarae N-Riese says:** Travelers have been bringing back numerous scrolls from the depths of darkness in the Outlands. They contain arcane knowledge specific to our classes. Only four are left that I seek. Keep a wary out for Theft of Thoughts, Color Slant, Cripple, and Dementia. Return any one of these to me and your reward shall be a scroll that can be found nowhere else.
end



## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19374" data-url="19374" class="tooltip-link link">Spell: Theft of Thought</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19378" data-url="19378" class="tooltip-link link">Spell: Color Slant</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19269" data-url="19269" class="tooltip-link link">Spell: Cripple</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19384" data-url="19384" class="tooltip-link link">Spell: Dementia</a>}

if(count > 0) then


repeat



>**Siladdarae N-Riese says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19386" data-url="19386" class="tooltip-link link">Spell: Boon of the Clear Mind</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19379" data-url="19379" class="tooltip-link link">Spell: Clarity II</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19381" data-url="19381" class="tooltip-link link">Spell: Recant Magic</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19215" data-url="19215" class="tooltip-link link">Spell: Wake of Tranquility</a>) (+1000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





