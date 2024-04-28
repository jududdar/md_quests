# Warlord Korehan

## Dialog

**You say:** `Hail`



e.self:Emote("stands tall and in a stiff, well-trained mode, salutes Soandso. 'Welcome to the district of Selia. 'ere, ye will find that we all be children of light 
end

## Turn-Ins



local count =  **You turn in:**  { [Indicolite Helm](/item/4911),  [Indicolite Breastplate](/item/4912),  [Indicolite Vambraces](/item/4913),  [Indicolite Bracer](/item/4914),  [Indicolite Gauntlets](/item/4915),  [Indicolite Greaves](/item/4916),  [Indicolite Boots](/item/4917)}

if(count > 0) then


repeat



>**Warlord Korehan says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**




