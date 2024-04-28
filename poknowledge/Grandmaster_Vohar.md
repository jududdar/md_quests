# Grandmaster Vohar

## Dialog

**You say:** `hail`



e.self:Emote("sneers coldly, his face contorting into a wretched, gruesome stare of hate. His eyes fill with an untamed, feral bloodlust as his low, hissing voice begins to seep from his throat. 'You stand within the district of Kartis 
end

## Turn-Ins



local count =  **You turn in:**  { [Shiverback-hide Jerkin](/item/1201),  [Shiverback-hide Armbands](/item/1202),  [Shiverback-hide Wristbands](/item/1203),  [Shiverback-hide Gloves](/item/1204),  [Shiverback-hide Leggings](/item/1205),  [Shiverback-hide Boots](/item/1206)}

if(count > 0) then


repeat



>**Grandmaster Vohar says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





