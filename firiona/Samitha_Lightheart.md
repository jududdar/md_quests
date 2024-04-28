# Samitha Lightheart
## Dialog

**You say:** `Hail`



>**Samitha Lightheart says:** And a good day to you, too! I have traveled here in the name of the Jaggedpine Treefolk to search out any new and [wonderful powers] that would aid us in preserving the wildlife back home. I have not been able to venture far from this outpost as the inhabitants of the nearby woods pose a great danger. I have decided to wait for more of my Treefolk to arrive before adventuring further.  There's safety in numbers, they always say.

**You say:** `wonderful powers`



>**Samitha Lightheart says:** From what I have gathered from the residents of this outpost and from others like myself, there are a fair number of scrolls to be found in the outlying areas.  These scrolls are said to contain new and powerful magic. I myself have found a few of these scrolls. But the problem is, I don't believe I have a complete collection. If you would care to [help] me, I'd be willing to trade some of the extra ones I have for some of the extras you may run across.

**You say:** `help`



>**Samitha Lightheart says:** I am still looking for four scrolls that I have not been able to locate. They are the scrolls of Circle of Winter, Circle of Summer, Spirit of Scale, and Form of the Howler. If you bring any of these back, I'll give you one of four very rare scrolls in my possession.
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Spirit of Scale](/item/19238),  [Spell: Form of the Howler](/item/19244),  [Spell: Circle of Winter](/item/19232),  [Spell: Circle of Summer](/item/19234)}

if(count > 0) then


repeat



>**Samitha Lightheart says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Call of Karana](/item/19235), [Spell: Upheaval](/item/19233), [Spell: Egress](/item/19236), [Spell: Glamour of Tunare](/item/19240)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





