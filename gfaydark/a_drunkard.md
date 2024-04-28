# a drunkard
## Dialog

**You say:** `tandan nybright`



>**a drunkard says:** How did you know my name? You must be from Felwithe. Hic.. Excuse my condition. I am not the man I was. I have had a [shocking experience].

**You say:** `shocking`



>**a drunkard says:** My daughters have become blood thirsty bandits. They went off to visit Antonica and when they returned they became bandits. They now attack every poor traveler who happens upon them. They have disgraced the name of Nybright. Will you [hunt the Nybright Sisters] or is this not to your liking?

**You say:** `hunt`



>**a drunkard says:** I am most thankful. Many adventurers would not help me with this matter. Go and seek out the Nybright sisters. I gave all four of them a Personalized Necklace. Return them all to me when the deed is done. May the Tribunal watch over you.

**You say:** `hail`



>**a drunkard says:** Can you -hic- . . . spare some copper or -hic- . . . silver? I just . . . -Hic- . . . need some change to buy something to drin . . Er . . Eat . -Hic-
end

## Turn-Ins





if **You turn in:** [Elven Wine](/item/13035)


>**a drunkard says:** Thank you kind sir <hic>, I am most grateful for your generosity.


 **You receive:** 0 (+150 exp)

elseif **You turn in:** [Dull Pearl Necklace](/item/13347), [Dull Pearl Necklace](/item/13349), [Dull Pearl Necklace](/item/13348), [Dull Pearl Necklace](/item/13350)


>**a drunkard says:** This is a sad day, but it was the just thing to do. The Nybright name will no longer be tarnished. Here you are my friend. This is a bit uncared for, but it is yours. My warrior days are over. Now go. I must be alone.


* __Faction:__ [Clerics of Tunare](/faction/226) (10)


* __Faction:__ [King Tearis Thex](/faction/279) (10)


* __Faction:__ [Anti-mage](/faction/5002) (7)


 **You receive:** eq.ChooseRandom( [Bearskin Gloves](/item/2314), 2007, 2005, 9003) (+1000 exp)




**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 3 or e.wp == 9 or e.wp == 15 or e.wp == 24 or e.wp == 26 or e.wp == 33) then


>**a drunkard says:** Please.. Can anyone spare some coppers? <Hic>.. Anyone?
end


