# Assassin Rysarieul

## Dialog

**You say:** `hail`



e.self:Emote("performs a deep, sweeping bow in a graceful and almost flamboyant display of greetings. 'Welcome, welcome to the district of Selia, my friend. I am Assassin Rysarieul 
end

## Turn-Ins



local count =  **You turn in:**  { [Woven Shadow Helm](/item/4901),  [Woven Shadow Chestplate](/item/4902),  [Woven Shadow Vambraces](/item/4903),  [Woven Shadow Bracer](/item/4904),  [Woven Shadow Gauntlets](/item/4905),  [Woven Shadow Greaves](/item/4906),  [Woven Shadow Boots](/item/4907)}

if(count > 0) then


repeat



>**Assassin Rysarieul says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





