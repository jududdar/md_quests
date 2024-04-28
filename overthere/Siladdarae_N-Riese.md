# Siladdarae N-Riese
## Dialog

**You say:** `Hail`



>**Siladdarae N-Riese says:** Hello, Soandso. This place is quite a formidable outpost, but it lacks the comforts of home. Once I have finished collecting some of my [missing scrolls], I'll be able to leave this place and all its hidden dangers.

**You say:** `missing scrolls`



>**Siladdarae N-Riese says:** Travelers have been bringing back numerous scrolls from the depths of darkness in the Outlands. They contain arcane knowledge specific to our classes. Only four are left that I seek. Keep a wary out for Theft of Thoughts, Color Slant, Cripple, and Dementia. Return any one of these to me and your reward shall be a scroll that can be found nowhere else.
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Theft of Thought](/item/19374),  [Spell: Color Slant](/item/19378),  [Spell: Cripple](/item/19269),  [Spell: Dementia](/item/19384)}

if(count > 0) then


repeat



>**Siladdarae N-Riese says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Boon of the Clear Mind](/item/19386), [Spell: Clarity II](/item/19379), [Spell: Recant Magic](/item/19381), [Spell: Wake of Tranquility](/item/19215)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





