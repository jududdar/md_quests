# High Priest Vasil

## Dialog

**You say:** `Hail`



>*High Priest Vasil closes his eyes and gives a deep, formal bow before Soandso. 'Welcome to Jeral, friend. I am Vasil, High Priest of Brell Serillis and resident master of the clerical arts in the district of Tanaan. If you have come in search of a mentor to guide you through the skills of your priesthood, then do not be discouraged by my own declaration of faith should it differ from yours. I cannot teach you how to know and be close to your deity in life, for only you may know that individually, but I can impart to you the fundamental basics that every priest, despite the object of their undying faith and devotion, wields in their life of service.'*
end

## Turn-Ins



local count =  **You turn in:**  { [Ethereal Mist Helm](/item/4881),  [Ethereal Mist Chestplate](/item/4882),  [Ethereal Mist Vambraces](/item/4883),  [Ethereal Mist Bracers](/item/4884),  [Ethereal Mist Gauntlets](/item/4885),  [Ethereal Mist Greaves](/item/4886),  [Ethereal Mist Boots](/item/4887)}

if(count > 0) then


repeat



>**High Priest Vasil says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





