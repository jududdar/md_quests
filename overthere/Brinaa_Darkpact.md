# Brinaa Darkpact
## Dialog

**You say:** `Hail`



>**Brinaa Darkpact says:** Hello, Soandso. It's nice to see more able bodies around this part of the outland. We came here in search of the magical powers that are supposed to exist in the ruins and dungeons of this area. We need you to bring back evidence of this power in the form of scrolls. I can't offer much coin in payment, but I do have some rare scrolls I already brought back that may interest you, if you wish to [help in the search].

**You say:** `help in the search`



>**Brinaa Darkpact says:** Excellent! Here is what we are still seeking. The scrolls of Death Pact. Upheaval. Yaulp IV. and Reckoning. If you return one of these to me. I'll release one of my rare scrolls to you.
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Death Pact](/item/19203),  [Spell: Upheaval](/item/19205),  [Spell: Yaulp IV](/item/19209),  [Spell: Reckoning](/item/19212)}

if(count > 0) then


repeat



>**Brinaa Darkpact says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Unswerving Hammer](/item/19210), [Spell: Heroic Bond](/item/19224), [Spell: Sunskin](/item/19420), [Spell: Word of Vigor](/item/19206)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





