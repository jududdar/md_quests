# High Priest Elikor

## Dialog

**You say:** `Hail`



e.self:Emote("raises a brow sharply, his beautiful features contorting into a flawless mask of regal superiority and a meager amusement in disdain toward Soandso. 'I see that the ranting of Selia's zealous crusaders of 'passion and honor' have become even too much for those who once believed themselves of the same cause. Indeed, how marvelously intriguing. Perhaps now you reside in Kartis to bathe in the cold embrace of the shadow 
end

## Turn-Ins



local count =  **You turn in:**  { [Ethereal Mist Helm](/item/4881),  [Ethereal Mist Chestplate](/item/4882),  [Ethereal Mist Vambraces](/item/4883),  [Ethereal Mist Bracers](/item/4884),  [Ethereal Mist Gauntlets](/item/4885),  [Ethereal Mist Greaves](/item/4886),  [Ethereal Mist Boots](/item/4887)}

if(count > 0) then


repeat



>**High Priest Elikor says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**


## On NPC Spawn

x = e.self:GetX();

y = e.self:GetY();

eq.set_proximity(x - 90, x + 90, y - 90, y + 90);
function event_enter(e)

**Signaled to:** 202273




