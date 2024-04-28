# Grave Lord Dreavud

## Dialog

**You say:** `Hail`



>*Grave Lord Dreavud peels back the upper right portion of his thin lips, giving a dark sneer of his gruesome features and horrific maw. 'You do not belong here! Return to Selia, where the light thrives. The shadow would embrace you, should you let it, but you are here for some righteous cause - one to destroy the shadow or learn of its secrets. You will find no success here, you pathetic little light crawler. Remain here and ignore my warning, and you will condemn yourself to consumption by the shadow should you further pursue its interests.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Umbral Platemail Helm](/item/4841),  [Umbral Platemail Breastplate](/item/4842),  [Umbral Platemail Vambraces](/item/4843),  [Umbral Platemail Bracer](/item/4844),  [Umbral Platemail Gauntlets](/item/4845),  [Umbral Platemail Greaves](/item/4846),  [Umbral Platemail Boots](/item/4847)}

if(count > 0) then


repeat



>**Grave Lord Dreavud says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





