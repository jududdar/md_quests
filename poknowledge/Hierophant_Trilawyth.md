# Hierophant Trilawyth

## Dialog

**You say:** `Hail`



>*Hierophant Trilawyth gives a gentle bow of his head in respect toward Soandso. 'The district of Tanaan welcomes you, traveler. The adepts of the city have come together collectively and as individuals in hopes of aiding our visitors as we are able. In my time upon Norrath, I served as a child of nature dedicated to Tunare, the Mother of All. Though my faith has not wavered and my philosophies of nature have only grown in this astral city, I am able to train any druid who is in need of gaining a better grasp upon their skills. Mind you, however, that I am not a preacher and will not guide you through the instruction of faith or spell, for it is these things you must acquire and perfect through your own trials.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Vermiculated Crown](/item/3801),  [Vermiculated Tunic](/item/3802),  [Vermiculated Armplates](/item/3803),  [Vermiculated Bracelet](/item/3804),  [Vermiculated Gloves](/item/3805),  [Vermiculated Leggings](/item/3806),  [Vermiculated Boots](/item/3807)}

if(count > 0) then


repeat



>**Hierophant Trilawyth says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





