# Vaean the Night


## Dialog

**You say:** `Hail`



>**Vaean the Night says:** Ahh, welcome! More souls to succumb to the inhabitants of the Outlands! My army of undead will grow stronger by the day, but it would be a pity if you perished before doing a [mortal bidding] for me.

**You say:** `mortal bidding`



>**Vaean the Night says:** I see it as a win-win situation for me. If you succeed, I'll gain more power from the knowledge you bring back to me. If you fail, you become another addition to my undead minions. Thus, you cannot fail me in returning a scroll of Splurt, Defoliation, Covergence, or Thrall of Bones. In return, I will part with a scroll of mine.
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Convergence](/item/19423),  [Spell: Defoliation](/item/19296),  [Spell: Splurt](/item/19294),  [Spell: Thrall of Bones](/item/19299)}

if(count > 0) then


repeat



>**Vaean the Night says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell.



 **You receive:** eq.ChooseRandom( [Spell: Minion of Shadows](/item/19297), [Spell: Sacrifice](/item/19421), [Spell: Scent of Terris](/item/19408), [Spell: Shadowbond](/item/19409)) (+500 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





