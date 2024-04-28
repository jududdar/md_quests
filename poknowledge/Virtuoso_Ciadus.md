# Virtuoso Ciadus

## Dialog

e.self:Emote("raises a brow sharply, his Teir'Dal heritage perfectly displayed in his sharp features twisted in a glare of flawless contempt. 'The district of Kartis 
## Turn-Ins



local count =  **You turn in:**  { [Imbrued Platemail Helm](/item/4861),  [Imbrued Platemail Breastplate](/item/4862),  [Imbrued Platemail Vambraces](/item/4863),  [Imbrued Platemail Bracer](/item/4864),  [Imbrued Platemail Gauntlets](/item/4865),  [Imbrued Platemail Greaves](/item/4866),  [Imbrued Platemail Boots](/item/4867)}

if(count > 0) then


repeat



>**Virtuoso Ciadus says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





