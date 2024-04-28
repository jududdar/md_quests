# Master Rixiz
## Dialog

**You say:** `hail`



>**Master Rixiz says:** You are on the grounds of the Brood of Kotiz. If you do not belong, you must leave at once. There shall be no [third rank skullcap] for you.

**You say:** `third rank skullcap`



if **Faction** >= Amiable then



>**Master Rixiz says:** I offer the third rank apprentice skullcap to those who wear the second. If that is you, then you will do the [bidding of the tower].


elseif **Faction** >= Indifferent then



>**Master Rixiz says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Rixiz says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `bidding of the tower`



if **Faction** >= Amiable then



>**Master Rixiz says:** Take this glass canopic. Within it you shall place a brain for me. The brain I seek is that of a sarnak crypt raider. Any shall do. The ones we seek should be near the Lake of Ill Omen. When you obtain the brain, you must quickly put it into the glass canopic with [embalming fluid]. When these are combined, the canopic shall seal and if you return it to me with your second rank skullcap, I shall hand you the next and final skullcap.



**You receive:**  [Brood Canopic](/item/17023)


elseif **Faction** >= Indifferent then



>**Master Rixiz says:** When you have shown more devotion to the Brood of Kotiz, we can discuss such things.


else



>**Master Rixiz says:** You are a true simpleton to think you can speak to me.  You are no ally to the Brood of Kotiz.  Begone, before I make your blood boil!


**You say:** `embalming fluid`



>**Master Rixiz says:** Embalming fluid is created through brewing, but do not drink it!! You can learn about the process of brewing on our grounds.
end

## Turn-Ins



local text1 = "You shall get no skullcap until I have the preserved raider brain and your second circle apprentice skullcap.";

local text2 = "I will not be bothered unless you bring me everything!";





if **Faction** >= Amiable and  **You turn in:** [Preserved Sarnak Brain](/item/12411), [Apprentice Skullcap - 2nd Rank](/item/4261)


>**Master Rixiz says:** You have done well. Here is your final apprentice skullcap.


* __Faction:__ [Brood of Kotiz](/faction/443) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


 **You receive:**  [Apprentice Skullcap - 3rd Rank](/item/4262) (+150 exp)

elseif **You turn in:** [Illegible Note: Boots](/item/14794)


>*Master Rixiz takes the note and after reading a few lines opens his eyes wide in astonishment. He looks up at you and stares at you a while before he says,*


>**Master Rixiz says:** You spoke to the Brothers? A common soldier such as yourself interested in silly stories to frighten broodlings? Fine, then. You shall know confidence, if you live. If you have the strength to stride into a lair, go before the owner, and kill that thing in its own home, you will acquire a small part of the virtue we as necromancers must master to ply our art. In the Frontier Mountains lives a unit of the troublesome burynai. Invade their home and destroy their leader. Bring me proof and two fire emeralds.

elseif **You turn in:** [Snaorfs Medallion](/item/14810), [Fire Emerald](/item/10033), [Fire Emerald](/item/10033)


>**Master Rixiz says:** Well done, here is your reference.


 **You receive:**  [Glosk's Reference: Boots](/item/14813) (+10000 exp)

**This NPC *should* return incorrect items given.**





