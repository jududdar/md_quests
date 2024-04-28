# Izarod Fristan
## Dialog

**You say:** `Hail`



>**Izarod Fristan says:** Hail there. Soandso. So you are ready to learn more about our ways? Do you wish to try and expand your knowledge of our arcane arts? Then venture far from here to the darkest depths of our once great empire and seek the minions that inhabit the ruins. The arcane powers will come in the form of [scrolls].

**You say:** `what scrolls?`



>**Izarod Fristan says:** Besides all the ones you will find. There are some that are only in my possession. To show that you have been successful on your journey, return one of splurt, defoliation, convergence, or thrall of bones. You then will be rewarded with one of my scrolls.
end

## Turn-Ins




local count =  **You turn in:**  { [Spell: Convergence](/item/19423),  [Spell: Defoliation](/item/19296),  [Spell: Splurt](/item/19294),  [Spell: Thrall of Bones](/item/19299)}

if(count > 0) then


repeat



>**Izarod Fristan says:** Here is the scroll that I promised. We have both gained much today. I hope to do business with you again soon. Farewell.



 **You receive:** eq.ChooseRandom( [Spell: Minion of Shadows](/item/19297), [Spell: Sacrifice](/item/19421), [Spell: Scent of Terris](/item/19408), [Spell: Shadowbond](/item/19409)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
