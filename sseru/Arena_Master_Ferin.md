# Arena Master Ferin
## Dialog

**You say:** `hail`



>**Arena Master Ferin says:** Hurry, hurry step right up and buy a ticket! Show your skills at battle! Amaze the crowds with your great skill! Buy a ticket from me, and when you think you are prepared for the fight give me the ticket!
end

## Turn-Ins





if( **You turn in:** [Arena Ticket](/item/29866)) then 


>**Arena Master Ferin says:** So you wish to show off your skills in the arena? Well come on let us see what you are made of! Be warned that this is a fight to the death, if a guard sees you fleeing like a coward they will assist in helping to finish you off!


eq.unique_spawn(eq.ChooseRandom(159108,159103,159109),0,0,-231,-1514,-68,128);

elseif( **You turn in:** [Arena Medal](/item/29867)) then 


>**Arena Master Ferin says:** Wonderful battle skills! You have pleased the audience. Here are a few coins for your valiant effort!


* __Faction:__ [Citizens of Seru](/faction/1499) (10)


* __Faction:__ [Hand of Seru](/faction/1484) (1)


* __Faction:__ [Heart of Seru](/faction/1486) (1)


* __Faction:__ [Eye of Seru](/faction/1485) (1)


* __Faction:__ [Shoulders of Seru](/faction/1487) (1)


* __Faction:__ [Katta Castellum Citizens](/faction/1502) (-5)


 **You receive:** 0 (+5000 exp)

**This NPC *should* return incorrect items given.**
