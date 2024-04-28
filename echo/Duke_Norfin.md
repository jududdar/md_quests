# Duke Norfin


## Dialog

if **Faction** >= Apprehensive then


**You say:** `hail`




>**Duke Norfin says:** Hello, Soandso. My guards seem to find you harmless enough, but I have yet to determine if you are trustworthy. We are always on the lookout for additional hands to assist in our work. Perhaps you are... sympathetic to our situation.


**You say:** `situation`




>**Duke Norfin says:** Those blasted Houses in Shadow Haven. They think they have the right to own all trade going through the Haven. Well it's about time they learn that trade will continue with or without their consent. I know a few people on the Trade Commission who understand the way things really work and they don't care who does the trading as long as they get their cut.


**You say:** `work`




>**Duke Norfin says:** Excellent! We like to keep changing who we use for deliveries. Keeps those dumb Defenders guessing and reduces the chances of goods not reaching their destination.


**You say:** `destination`




>**Duke Norfin says:** I have an important shipment coming from Katta Castellum that's late. The courier who was picking up the shipment should still be there. I'd like for you to go over there and see what the hold up is. Take this note and show it to Jarin Lorean so he knows you're on official business. Report back to me with news. Better yet, return with the shipment if you can.



**You receive:**  [Note to Jarin](/item/19841)


else


>**Duke Norfin says:** You have a lot of nerve wandering in here. We'll be watching you carefully. Try anything and it will be the last thing you ever try.
end

## Turn-Ins





if **Faction** >= Apprehensive and  **You turn in:** [Smuggled Goods](/item/19840)


>**Duke Norfin says:** Excellent work. I'm glad you were able to collect this shipment. The buyers were getting anxious to have it delivered. Come back later and I may have another job for you.


* __Faction:__ [Haven Smugglers](/faction/1542) (25)


* __Faction:__ [Lake Recondite Bandits](/faction/1559) (2)


* __Faction:__ [House of Fordel](/faction/1510) (-12)


* __Faction:__ [House of Midst](/faction/1511) (-12)


* __Faction:__ [House of Stout](/faction/1512) (-12)


 **You receive:** 0 (+25000 exp)

**This NPC *should* return incorrect items given.**