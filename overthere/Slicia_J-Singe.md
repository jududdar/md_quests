# Slicia J-Singe
## Dialog

**You say:** `Hail`



>**Slicia J-Singe says:** Why is it that you have come to this place? If you are coming here to search for [magical scrolls], just get back on that so-called ship you came here on and forget everything you thought you heard.

**You say:** `magical scrolls`



>**Slicia J-Singe says:** Is your hearing failing you!? Unless you [have something I need]. be gone!

**You say:** `i have something you need`



>**Slicia J-Singe says:** I must have the scrolls of Gift of Xev. Bristlebane's Bundle. Quiver of Marr. and the Scars of Sigil. If you don't have one of these. leave my sight!  If you do. I think we can work up a fair trade.
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Bristlebane\`s Bundle](/item/19351),  [Spell: Gift of Xev](/item/19347),  [Spell: Quiver of Marr](/item/19354),  [Spell: Scars of Sigil](/item/19358)}

if(count > 0) then


repeat



>**Slicia J-Singe says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Boon of Immolation](/item/19368), [Spell: Scintillation](/item/19346), [Spell: Vocarate: Fire](/item/19355), [Spell: Vocarate: Air](/item/19357)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





