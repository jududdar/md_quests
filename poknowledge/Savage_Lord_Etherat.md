# Savage Lord Etherat


## Dialog

**You say:** `Hail`



>*Savage Lord Etherat performs an ancient, graceful gesture that is seemingly arcane in nature, though no energy can be felt entering or dispersing in the room. 'Tanaan welcomes you to its midst, traveler, There is much to be found in the whole of New Tanaan and specifically, the great library of Myrist. However, there is only so much that the tangible world can teach you. friend. for true, infinite knowledge lies eternally beyond the confines of material and astral domains. Within yourself. your very spirit and the spirits that surround you lays the key to true enlightenment and self-progress. Should you follow the path of the Beastlords. then I may be of aid in guiding your further toward the realization of your potential and the true elements surrounding you.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Anthemion Wristguard](/item/7817),  [Anthemion Boots](/item/7818),  [Anthemion Leggings](/item/7819),  [Anthemion Gloves](/item/7832),  [Anthemion Jerkin](/item/7833),  [Anthemion Armbands](/item/7834),  [Anthemion Skullcap](/item/7835)}

if(count > 0) then


repeat



>**Savage Lord Etherat says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





