# High Priest Eliwan

## Dialog

**You say:** `Hail`



e.self:Emote("makes an almost unearthly graceful gesture as he bows politely at the waist in formal greetings. 'May the light of Tunare shine brightly upon your fate, my friend, and may the purity of goodly virtues guide your convictions. I am High Priest Eliwan, former scholar, historian, and spiritual leader in the faith dedicated toward the Mother of All. In the era that housed my life, Takish\`Hiz was my home in the beautiful forest of Elddar, the shining crown jewel of Tunare's grace and infinite splendor. We were at peace then 
end

## Turn-Ins



local count =  **You turn in:**  { [Ethereal Mist Helm](/item/4881),  [Ethereal Mist Chestplate](/item/4882),  [Ethereal Mist Vambraces](/item/4883),  [Ethereal Mist Bracers](/item/4884),  [Ethereal Mist Gauntlets](/item/4885),  [Ethereal Mist Greaves](/item/4886),  [Ethereal Mist Boots](/item/4887)}

if(count > 0) then


repeat



>**High Priest Eliwan says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





