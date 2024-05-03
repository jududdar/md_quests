# Utandar Rizndown


## Dialog

**You say:** `Hail`



>**Utandar Rizndown says:** It is good to see our numbers growing on this land. Welcome! May your travels be as prosperous as mine have. There are many [new powers] to be gained from this land.

**You say:** `new powers`



>**Utandar Rizndown says:** The new powers are scrolls that give us access to new and powerful spells. My collection is almost complete. I am simply [lacking] four more and then I will return back to the homeland.

**You say:** `lacking`



>**Utandar Rizndown says:** I am missing the scroll Atol's Spectral Shackles, Tears of Druzzil, Inferno of Al'kabor, and Pillar of Frost. Should you run into one, bring it to me and I'll perform an exchange for another scroll.
end



## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19315" data-url="19315" class="tooltip-link link">Spell: Atol\`s Spectral Shackles</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19322" data-url="19322" class="tooltip-link link">Spell: Inferno of Al\`Kabor</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19318" data-url="19318" class="tooltip-link link">Spell: Pillar of Frost</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19319" data-url="19319" class="tooltip-link link">Spell: Tears of Druzzil</a>}

if(count > 0) then


repeat



>**Utandar Rizndown says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19329" data-url="19329" class="tooltip-link link">Spell: Tears of Solusek</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19320" data-url="19320" class="tooltip-link link">Spell: Abscond</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19324" data-url="19324" class="tooltip-link link">Spell: Thunderbold</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19317" data-url="19317" class="tooltip-link link">Spell: Tishan\`s Discord</a>) (+1000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





