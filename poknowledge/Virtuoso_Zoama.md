# Virtuoso Zoama


## Dialog

**You say:** `Hail`



>*Virtuoso Zoama gives a warm smile of her comely features and a delicate bow of her head in greetings. 'Good day to you, Soandso, and welcome to the district of Selia. You will find that the light and mortal virtues of justly kindness, honor, valor, and untainted passion are represented in full upon this plane in our midst. Rather, each of the three districts that house the adepts of New Tanaan represent and fulfill the core elements and pure essence of mortal virtues within the universe, we collectively embody that of the light. I'm certain you will find yourself at home among us, and for this we are pleased and grateful. During your stay with us, I would suggest that you seek our adepts and merchants, for the knowledge we hold cannot be found in the library of Myrist. for it is one that is the key to purity and faith of the light. If you are one of the bardic traditions, then I may be of assistance to you should you need training the ways of your skills. Otherwise, it has been a pleasure to make your acquaintance.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Imbrued Platemail Helm](/item/4861),  [Imbrued Platemail Breastplate](/item/4862),  [Imbrued Platemail Vambraces](/item/4863),  [Imbrued Platemail Bracer](/item/4864),  [Imbrued Platemail Gauntlets](/item/4865),  [Imbrued Platemail Greaves](/item/4866),  [Imbrued Platemail Boots](/item/4867)}

if(count > 0) then


repeat



>**Virtuoso Zoama says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





