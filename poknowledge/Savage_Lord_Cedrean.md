# Savage Lord Cedrean


## Dialog

**You say:** `Hail`



>*Savage Lord Cedrean in an almost arcane motion, gives a mystic gesture of ancient greetings. 'The light of Selia shines upon you most brightly, Soandso. Be at ease, and know that all answers you seek will be delivered in time. The library of Myrist, though lacking the purity of the virtues we hold most dear to our selves in valiant memory of our mortal endeavors, is truly an unrivaled source of infinite knowledge. However, if you seek the comfort of your own light and goodly virtues, then Selia shall provide whatever it can to accommodate your needs while in our midst. Unfortunately, the ruling of the council has limited each individual citizen of the city to one particular specialty so that each have their equal opportunity to share their unique knowledge. In my former life, I was a master of the beasts and crusader of Mithaniel Marr. If you share the same profession as I and are in need of training, then I am more than pleased to oblige you.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Anthemion Wristguard](/item/7817),  [Anthemion Boots](/item/7818),  [Anthemion Leggings](/item/7819),  [Anthemion Gloves](/item/7832),  [Anthemion Jerkin](/item/7833),  [Anthemion Armbands](/item/7834),  [Anthemion Skullcap](/item/7835)}

if(count > 0) then


repeat



>**Savage Lord Cedrean says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





