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



local count =  **You turn in:**  { [Spell: Atol\`s Spectral Shackles](/item/19315),  [Spell: Inferno of Al\`Kabor](/item/19322),  [Spell: Pillar of Frost](/item/19318),  [Spell: Tears of Druzzil](/item/19319)}

if(count > 0) then


repeat



>**Utandar Rizndown says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Tears of Solusek](/item/19329), [Spell: Abscond](/item/19320), [Spell: Thunderbold](/item/19324), [Spell: Tishan\`s Discord](/item/19317)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





