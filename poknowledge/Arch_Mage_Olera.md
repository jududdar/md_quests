# Arch Mage Olera



## Dialog

**You say:** `Hail`



>*Arch Mage Olera gives an almost unearthly graceful gesture in warm welcoming of Soandso. 'May the light of honor, valor, and untainted passion guide you through the dark turmoil of this dreaded era. I am very pleased to see you before us, friend, for the children of the light must all come together in this dark hour of Norrath and the universe's fate. If you have need of guidance in the ways of the elements, then what humble knowledge I have is at your disposal, my friend.'*
end
## Turn-Ins



local count =  **You turn in:**  { [Apothic Crown](/item/1239),  [Apothic Robe](/item/1240),  [Apothic Sleeves](/item/1241),  [Apothic Warband](/item/1242),  [Apothic Gloves](/item/1243),  [Apothic Kilt](/item/1244),  [Apothic Boots](/item/1245)}

if(count > 0) then


repeat



>**Arch Mage Olera says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





