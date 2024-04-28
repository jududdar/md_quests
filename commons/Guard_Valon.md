# Guard Valon


## Dialog

**You say:** `hail`



>**Guard Valon says:** Greetings, traveler! If you wish to walk upon the road to Freeport, you will pay the toll of two silver pieces. And you should. It is not safe to stray from the pathway. There are many [dangers in the Commonlands].

**You say:** `dangers in the commonlands`



>**Guard Valon says:** The orcs have been a nuisance of late. Many travelers have perished at the hands of the orc pawns. Would you like to [assist the Freeport Militia] in ridding the lands of the orcs?

**You say:** `assist the freeport militia`



>**Guard Valon says:** Sir Lucan would be proud!! Patrol the Commonlands and watch for any orc pawns. Should you find any orc pawn picks on them, I will pay you for every four you return to me. Be off, then! For the glory of Freeport!!

**You say:** `hunt dervish cutthroats`



if **Faction** >= Amiable then



>**Guard Valon says:** You will make a fine reserve!! Take this bag and fill it with Dervish Cutthroat Insignia Rings. When they are combined and returned to me you shall be accepted into the Reserve Freeport Militia!!



**You receive:**  [Bag for Cutthroat Rings](/item/17975)


elseif **Faction** >= Indifferent then



>**Guard Valon says:** Doing away with more orc pawns, and perhaps turning in the orc pawn picks to me, may increase my trust in you.


else



>**Guard Valon says:** Stand where you are, citizen. I believe you are wanted by the Freeport Militia.

end

## Turn-Ins



local text = "I cannot reward you until you hand me four orc pawn picks. So says Captain Hazran.";


if **You turn in:** [Orc Pawn Pick](/item/13885), [Orc Pawn Pick](/item/13885), [Orc Pawn Pick](/item/13885), [Orc Pawn Pick](/item/13885)


>**Guard Valon says:** You have done well. Keep up the good work and we may trust you to [hunt dervish cutthroats] which in turn will allow you to join the Reserve Freeport Militia.


* __Faction:__ [The Freeport Militia](/faction/330) (3)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)


* __Faction:__ [Knights of Truth](/faction/281) (-1)


* __Faction:__ [Priests of Marr](/faction/362) (-1)


 **You receive:** 0 (+500 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Bag of Cutthroat Rings](/item/12272)


>**Guard Valon says:** Excellent work, Soandso!! You are quite formidable. Maybe soon you shall aid in our efforts to rid the Northern part of Freeport of the paladins!! Until then keep up the good work. Take this Armory Token to the Militia Armorer in the Militia House in Freeport to receive your tunic. He may not be there, but I assure you he will show up at some time. On the second floor. Hail Sir Lucan!!


* __Faction:__ [The Freeport Militia](/faction/330) (10)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (1)


* __Faction:__ [Knights of Truth](/faction/281) (-1)


* __Faction:__ [Priests of Marr](/faction/362) (-1)


 **You receive:**  [Militia Armory Token](/item/12273) (+500 exp)

**This NPC *should* return incorrect items given.**
;

