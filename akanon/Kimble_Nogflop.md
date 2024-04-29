# Kimble Nogflop


## Dialog

**You say:** `hail`



>**Kimble Nogflop says:** Greetings! I am the keeper of this zoo. I advise you to stay on the upper tiers to observe the animals.

**You say:** `regurgitonic`



if **Faction** >= Apprehensive then



>**Kimble Nogflop says:** I formulate the Regurgitonic myself. My animals kept eating the occasional spectator here and there. Femurs and ribs kept getting stuck inside, not to mention a few platinum pieces. Sometimes my batch would come out wrong and the animals would go berserk!! I hope I got the formula right this time.


else



>**Kimble Nogflop says:** You must show a greater allegiance to the Gemchoppers before we can speak with you. Search the hills for rogue clockworks. Captain Compolten shall accept two of their blackboxes and you shall prove your loyalty to our hall.

end

## Turn-Ins



if **Faction** >= Apprehensive and  **You turn in:** [Flask of Nitrates](/item/13945)) then 


>**Kimble Nogflop says:** The flask of nitrates I sent for!! As was the deal, here is my [Regurgitonic]. Give it to whoever may need it and they will surely cough up whatever may be inside them with no harm to them whatsoever.





* __Faction:__ [Gem Choppers](/faction/255) (10)



* __Faction:__ [Merchants of Ak`Anon](/faction/288) (2)



* __Faction:__ [King Ak`Anon](/faction/333) (2)



* __Faction:__ [Dark Reflection](/faction/238) (-2)



* __Faction:__ [Clan Grikbar](/faction/1604) (-1)



 **You receive:** eq.ChooseRandom( [Regurgitonic](/item/12140), [Regurgitonic](/item/12139)) (+100 exp)


**This NPC *should* return incorrect items given.**
