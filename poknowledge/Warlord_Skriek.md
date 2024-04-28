# Warlord Skriek


## Turn-Ins



local count =  **You turn in:**  { [Legionnaire Scale Helm](/item/5174),  [Legionnaire Scale Breastplate](/item/5175),  [Legionnaire Scale Pauldron](/item/5176),  [Legionnaire Scale Vambraces](/item/5177),  [Legionnaire Scale Bracers](/item/5178),  [Legionnaire Scale Gauntlets](/item/5179),  [Legionnaire Scale Greaves](/item/5180),  [Legionnaire Scale Boots](/item/5181)}

if(count > 0) then


repeat



>**Warlord Skriek says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





