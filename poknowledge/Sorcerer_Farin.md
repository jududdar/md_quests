# Sorcerer Farin

## Dialog

**You say:** `Hail`



>*Sorcerer Farin gives a deep, respectful nod of his head toward Soandso. 'Welcome, Soandso. I am Sorcerer Farin, ancient wizard of Erudin and head sorcerer of Selia. In light of your arrival, those who walk the path of light and hold the virtues of honor and justice high in their spirits. I offer my aid to any that would be so obliged as to accept it. In my former years, I was one of few guild masters in the newfound city of Erudin and what knowledge I have of that past is at your disposal.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Carmine Turban](/item/1225),  [Carmine Robe](/item/1226),  [Carmine Sleeves](/item/1227),  [Carmine Trinket](/item/1228),  [Carmine Gloves](/item/1229),  [Carmine Pants](/item/1230),  [Carmine Boots](/item/1231)}

if(count > 0) then


repeat



>**Sorcerer Farin says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





