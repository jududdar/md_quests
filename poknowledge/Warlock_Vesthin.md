# Warlock Vesthin

[Warlock Vesthin](/npc/202256) is a level 61 Iksar GM Necromancer that spawns in [Plane of Knowledge](/zone/202).

Their primary faction is [Inhabitants of Tanaan](/faction/1636).


## Dialog
**You say:** `Hail`

e.self:Emote("peels back his thin, scaled lips, revealing a row of flawless tiny fangs in a grim gaze that brings even the bravest paladin to a moment of hesitation. 'We are somewhat. . . put off by your presence among us, though this is something I'm certain will not take long to remedy once you understand the peril you have come into. Strange, however, that you would wander into Kartis of either your own free will or the misdirection of your own footsteps. Perhaps you feel that you may learn from us what the other minions of the shadow have kept in their souls to use against us. I assure you, no such thing will come as you expect. Begone from this place, Soandso, for you will only burden or distract the best of us with the temptation to lure you into our folds. Aaaah, yes, that is the action of Kartis 





## Turn-Ins

local count =  **You turn in:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_640.png" alt="" /> <a
                                href="/item/1232" data-url="1232" class="tooltip-link link">Blighted Skullcap</a>, 1233, 1234, 1235, 1236, 1237, 1238 x 1
if(count > 0) then
repeat
>**Warlock Vesthin says:** Thank you, Soandso.
 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_957.png" alt="" /> <a
                                href="/item/10028" data-url="10028" class="tooltip-link link">Peridot</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/10037" data-url="10037" class="tooltip-link link">Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/22503" data-url="22503" class="tooltip-link link">Blue Diamond</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_966.png" alt="" /> <a
                                href="/item/15981" data-url="15981" class="tooltip-link link">Raw Diamond</a>) (+300000 exp)

 
count = count - 1;
until count == 0;

**This NPC *should* return incorrect items given.**






