# Izarod Fristan


## Dialog

**You say:** `Hail`



>**Izarod Fristan says:** Hail there. Soandso. So you are ready to learn more about our ways? Do you wish to try and expand your knowledge of our arcane arts? Then venture far from here to the darkest depths of our once great empire and seek the minions that inhabit the ruins. The arcane powers will come in the form of [scrolls].

**You say:** `what scrolls?`



>**Izarod Fristan says:** Besides all the ones you will find. There are some that are only in my possession. To show that you have been successful on your journey, return one of splurt, defoliation, convergence, or thrall of bones. You then will be rewarded with one of my scrolls.
end



## Turn-Ins




local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19423" data-url="19423" class="tooltip-link link">Spell: Convergence</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19296" data-url="19296" class="tooltip-link link">Spell: Defoliation</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19294" data-url="19294" class="tooltip-link link">Spell: Splurt</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19299" data-url="19299" class="tooltip-link link">Spell: Thrall of Bones</a>}

if(count > 0) then


repeat



>**Izarod Fristan says:** Here is the scroll that I promised. We have both gained much today. I hope to do business with you again soon. Farewell.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19297" data-url="19297" class="tooltip-link link">Spell: Minion of Shadows</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19421" data-url="19421" class="tooltip-link link">Spell: Sacrifice</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19408" data-url="19408" class="tooltip-link link">Spell: Scent of Terris</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19409" data-url="19409" class="tooltip-link link">Spell: Shadowbond</a>) (+1000 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
