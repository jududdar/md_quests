# Grave Lord Vizurik

## Dialog

**You say:** `Hail`



>*Grave Lord Vizurik peels back the upper right portion of his thin lips, giving a dark sneer of his gruesome features and horrific maw. 'You do not belong here! Return to Selia, where the light thrives. The shadow would embrace you, should you let it, but you are here for some righteous cause - one to destroy the shadow or learn of its secrets. You will find no success here, you pathetic little light crawler. Remain here and ignore my warning, and you will condemn yourself to consumption by the shadow should you further pursue its interests.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Greenmist Helm](/item/5166),  [Greenmist Breastplate](/item/5167),  [Greenmist Vambraces](/item/5168),  [Greenmist Bracer](/item/5169),  [Greenmist Greaves](/item/5171),  [Greenmist Boots](/item/5172),  [Greenmist Mask](/item/5173)}

if(count > 0) then


repeat



>**Grave Lord Vizurik says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





