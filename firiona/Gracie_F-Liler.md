# Gracie F-Liler
## Dialog

**You say:** `hail`



>**Gracie F-Liler says:** It's so good to see new faces, not to mention more adventurers in this area. On some nights, the sounds that come from the nearby hills will scare even the hardiest of travelers. I volunteered in the name of the Keepers of the Art to help locate any [new spell scrolls] that might surface. Maybe you will have a successful journey and find some of these scrolls yourself.

**You say:** `new spell scrolls`



>**Gracie F-Liler says:** I have recently come into possession of some of these scrolls. They seem to be very promising in adding to the strengths of our occupation. Some more good news is that I have a few extra of these scrolls. Perhaps you might have or find an extra of your own and be willing to trade? In case you are interested, I am looking for the scrolls Theft of Thought, Color Slant, Cripple, and lastly Dementia. Bring me one of these and I'll make an even trade.

**You say:** `fyrefly`



>**Gracie F-Liler says:** Do you like her? I found her injured one day just outside the outpost. She just seems to hang around now. I don't blame her though. It's much safer in here than out there.
end

## Turn-Ins



local count =  **You turn in:**  { [Spell: Color Slant](/item/19378),  [Spell: Cripple](/item/19269),  [Spell: Dementia](/item/19384),  [Spell: Theft of Thought](/item/19374)}

if(count > 0) then


repeat



>**Gracie F-Liler says:** Here is the scroll that I promised. We have both gained much knowledge today. I hope to do business with you again soon. Farewell!



 **You receive:** eq.ChooseRandom( [Spell: Boon of the Clear Mind](/item/19386), [Spell: Clarity II](/item/19379), [Spell: Recant Magic](/item/19381), [Spell: Wake of Tranquility](/item/19215)) (+1000 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**





