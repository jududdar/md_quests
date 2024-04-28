# Assassin Mirot


## Dialog

**You say:** `Hail`



e.self:Emote("gives a sharply raised brow and cruelly wicked smirk, his comely features contorted in a sinister mask of disgust and amusement. 'Well, how charming of you to find it within your heart to visit Kartis, my dear pathetic Soandso. Do not think that you will be received in the manner you had hoped, for we are in the city of knowledge where tolerance for all beings to one extent or another is mandatory. Aaaah, yes, we will tolerate your existence among us, but only for the amusement of watching you squirm uncomfortably when presented with the truth of our purpose. Even further the amusement would stretch is if you would have the audacity to train from one of our adepts 
end

## Turn-Ins



local count =  **You turn in:**  { [Woven Shadow Helm](/item/4901),  [Woven Shadow Chestplate](/item/4902),  [Woven Shadow Vambraces](/item/4903),  [Woven Shadow Bracer](/item/4904),  [Woven Shadow Gauntlets](/item/4905),  [Woven Shadow Greaves](/item/4906),  [Woven Shadow Boots](/item/4907)}

if(count > 0) then


repeat



>**Assassin Mirot says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





