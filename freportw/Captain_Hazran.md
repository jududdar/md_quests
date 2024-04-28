# Captain Hazran
## Dialog

**You say:** `hail`



>**Captain Hazran says:** Hail, citizen! Welcome to the Freeport Militia House. It is time for you to serve the state. You will assist us in our war with [Clan Deathfist] before you are truly accepted into our city. We urge you to be all we command you to be.

**You say:** `clan deathfist`



>**Captain Hazran says:** Clan Deathfist are the orcs of the Commonlands. They are a nuisance and Sir Lucan has ordered their extermination. You will go forth into the Commonlands and kill these orcs. Clan Deathfist members are known to wear a clan belt. Bring a belt to me as proof of each death and you shall receive your wages and prove your allegiance to Freeport and all that is good.
end

## Turn-Ins




local count =  **You turn in:**  { [Deathfist Slashed Belt](/item/13916)}, 1

if(count > 0) then


repeat



>**Captain Hazran says:** Good work, warrior. You are good militia material. Beware though, there are some who dare to call us foe. You have performed so well!



* __Faction:__ [The Freeport Militia](/faction/330) (5)



* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)



* __Faction:__ [Knights of Truth](/faction/281) (-1)



* __Faction:__ [Priests of Marr](/faction/362) (-1)



 **You receive:** 0 (+9350 exp)



count = count - 1;


until count == 0;

**This NPC *should* return incorrect items given.**
;

