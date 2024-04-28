# Cappi McTarnigal
## Dialog

**You say:** `Hail`



>**Cappi McTarnigal says:** Hail there, Soandso! If you are not a [member of the White Rose], then it be best that you stay on the lower level. This here floor is for honest ...ermm respectable rogues only.

**You say:** `member of the white rose`



if **Faction** >= Indifferent then 



>**Cappi McTarnigal says:** I hope that you are indeed respectable and loyal to Halas and the Rogues of the White Rose. To do otherwise would bring the wrath of the Six Hammers down on you. But enough with talk! Our caravan to the frigid north leaves in less than two days. and we are short on mammoth calf hides. Return four of them and you will be given items that show your loyalty to our Clan.



**Signaled to:**  [Ysanna MacGibbon](/npc/29070)


else



>**Cappi McTarnigal says:** I will take these as a donation for I can only reward those who are 'respectable.

end

## Turn-Ins



if **Faction** >= Indifferent and  **You turn in:** [Mammoth Calf Hide](/item/5243), [Mammoth Calf Hide](/item/5243), [Mammoth Calf Hide](/item/5243), [Mammoth Calf Hide](/item/5243)



>**Cappi McTarnigal says:** You returned? We believed the gnoll pups got you. The caravan has already left, and these do me little good now. But, as I said before, one must remain respectable. Here is what I promised.





* __Faction:__ [Rogues of the White Rose](/faction/305) (5)



 **You receive:** eq.ChooseRandom( [Black Wolf Armplates](/item/5238), [Black Wolf Bracers](/item/5239), [Black Wolf Boots](/item/5242), [Black Wolf Cape](/item/5236), [Black Wolf Collar](/item/5233), [Black Wolf Crown](/item/5231), [Black Wolf Gloves](/item/5240), [Black Wolf Legplates](/item/5241), [Black Wolf Mail](/item/5234), [Black Wolf Mask](/item/5232), [Black Wolf Pauldrons](/item/5235), [Black Wolf Waistband](/item/5237)) (+2500 exp)




**This NPC *should* return incorrect items given.**





