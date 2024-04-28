# Josper Kenshed
## Dialog

**You say:** `hail`



>**Josper Kenshed says:** Come forward and speak.  What is it you seek within these walls?  Let it be the knowledge of wizardry. for that is what we are.  Only a [servant of wizardry] should be within these walls.

**You say:** `servant of wizardry`



>**Josper Kenshed says:** A servant. you say?  If you be a young apprentice. perhaps you might assist me? I could use you to [collect components].  If you believe yourself to be beyond such things. you may wish to assist me with a [special matter].

**You say:** `collect component`



if **Faction** >= Amiable then 



**You say:** `collect component`





>**Josper Kenshed says:** Of course you may assist me!! We have much need of a certain item which can only be found in the frigid peaks of Everfrost. There you shall find creatures called ice goblins. Take this bag and fill it with ice goblin beads and be sure to combine them before you return them. Well, then... Off with you!! And be quick about it and I shall give you a fine wizard's weapon. None of this rust-covered garbage offered by our associates!




**You receive:**  [Empty Bag](/item/17944)



**You say:** `special matter`





>**Josper Kenshed says:** It seems my last apprentice was sent into Toxxulia to test a spell I call Ice Capade, well, everyone else calls it Column of Frost, how droll! Anyway... he never returned. I fear he is nothing more than BONES, though I hope I'm wrong. Could you find good old Ilanic and ask him, [where is the scroll]?! I do not wish it to fall into enemy hands. Return it and I shall let you keep the scroll. Oh yes, It is only half of a spell. I forgot to send him the full scroll. I imagine that is why he was not victorious.




elseif **Faction** >= Indifferent then



>**Josper Kenshed says:** The Crimson Hands have no quarrel with you, but we cannot truly trust you as yet.





else



>**Josper Kenshed says:** The Crimson Hands will have nothing to do with you. Perhaps only your death shall improve our relations.


end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Bag of Ice Necklaces](/item/13898)


>**Josper Kenshed says:** Well done, my young apprentice. I call you apprentice for you are nothing but a spark to my fire. This is the final component for my greatest creation. AHA!! I call it - iced tea!! Never again shall I boil under the hot sun. As for you, take this. It should serve you well. Now go away. There is no iced tea for you.





* __Faction:__ [Crimson Hands](/faction/233) (15)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-2)


* __Faction:__ [High Guard of Erudin](/faction/267) (2)


 **You receive:**  [Servants Staff](/item/12208) (+1000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Half of a Spell](/item/12207)


>**Josper Kenshed says:** I see you found Ilanic. How is he doing? I hope he is well. As for you, you may have the spell Ice Capa... err, I mean Column of Frost. Don't go and lose it now.





* __Faction:__ [Crimson Hands](/faction/233) (5)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


* __Faction:__ [High Guard of Erudin](/faction/267) (1)


 **You receive:**  [Spell: Column of Frost](/item/15380) (+1000 exp)



**This NPC *should* return incorrect items given.**
;

