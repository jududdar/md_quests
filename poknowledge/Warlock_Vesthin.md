# Warlock Vesthin

## Dialog

**You say:** `Hail`



e.self:Emote("peels back his thin, scaled lips, revealing a row of flawless tiny fangs in a grim gaze that brings even the bravest paladin to a moment of hesitation. 'We are somewhat. . . put off by your presence among us, though this is something I'm certain will not take long to remedy once you understand the peril you have come into. Strange, however, that you would wander into Kartis of either your own free will or the misdirection of your own footsteps. Perhaps you feel that you may learn from us what the other minions of the shadow have kept in their souls to use against us. I assure you, no such thing will come as you expect. Begone from this place, Soandso, for you will only burden or distract the best of us with the temptation to lure you into our folds. Aaaah, yes, that is the action of Kartis 
end

## Turn-Ins



local count =  **You turn in:**  { [Blighted Skullcap](/item/1232),  [Blighted Robe](/item/1233),  [Blighted Sleeves](/item/1234),  [Blighted Armband](/item/1235),  [Blighted Gloves](/item/1236),  [Blighted Trousers](/item/1237),  [Blighted Boots](/item/1238)}

if(count > 0) then


repeat



>**Warlock Vesthin says:** Thank you, Soandso.



 **You receive:** eq.ChooseRandom( [Peridot](/item/10028), 10037, 22503, 15981) (+300000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





