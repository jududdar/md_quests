# Oracle Guwan

## Dialog

**You say:** `hail`



>*Oracle Guwan curls back his thin, reptilian-like lips, baring a two rows of jagged, unkempt teeth in a sinister sneer of hate. 'Little worm speaks? How quaint and disgusting you are, worm, and how pathetic. Begone from Kartis, little worm, you do not belong among the shadows. Your ears will melt when the shadow speaks the secrets of its mind and infinite memory. But. . . hehehe. . . but. yes. maybe you little worms think yourselves beyond the shadow's venomous tongue. . . maybe you are. . . heheheh. . . maybe you should stay, worm, and learn from Guwan. He knows much of the shadow's words, the shadow that taints and subdues the world of spirits to its will. Yes, stay worm, and learn from the shadow. . . see how. . . hehehehe. . . see how brave you truly are.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Rune Etched Helm](/item/4871),  [Rune Etched Chestplate](/item/4872),  [Rune Etched Vambraces](/item/4873),  [Rune Etched Bracer](/item/4874),  [Rune Etched Gauntlets](/item/4875),  [Rune Etched Greaves](/item/4876),  [Rune Etched Boots](/item/4877)}

if(count > 0) then


repeat



>**Oracle Guwan says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





