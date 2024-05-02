# Vaean the Night


## Dialog

**You say:** `Hail`



>**Vaean the Night says:** Ahh, welcome! More souls to succumb to the inhabitants of the Outlands! My army of undead will grow stronger by the day, but it would be a pity if you perished before doing a [mortal bidding] for me.

**You say:** `mortal bidding`



>**Vaean the Night says:** I see it as a win-win situation for me. If you succeed, I'll gain more power from the knowledge you bring back to me. If you fail, you become another addition to my undead minions. Thus, you cannot fail me in returning a scroll of Splurt, Defoliation, Covergence, or Thrall of Bones. In return, I will part with a scroll of mine.
end

## Turn-Ins



local count =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19423" data-url="19423" class="tooltip-link link">Spell: Convergence</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19296" data-url="19296" class="tooltip-link link">Spell: Defoliation</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19294" data-url="19294" class="tooltip-link link">Spell: Splurt</a>,  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19299" data-url="19299" class="tooltip-link link">Spell: Thrall of Bones</a>}

if(count > 0) then


repeat



>**Vaean the Night says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell.



 &#127873; **You receive:** eq.ChooseRandom( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19297" data-url="19297" class="tooltip-link link">Spell: Minion of Shadows</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19421" data-url="19421" class="tooltip-link link">Spell: Sacrifice</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19408" data-url="19408" class="tooltip-link link">Spell: Scent of Terris</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/19409" data-url="19409" class="tooltip-link link">Spell: Shadowbond</a>) (+500 exp)

 



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





