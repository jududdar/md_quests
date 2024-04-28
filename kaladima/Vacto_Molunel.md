# Vacto Molunel
## Dialog

**You say:** `Hail`



>**Vacto Molunel says:** Well met, Soandso!  I am Vacto Molunel.  If you are seeking to outfit yourself with the finest weapons in all of Kaladim. I am the one to see.  I also posses a [rare talent] you might find useful.

**You say:** `rare talent`



if **Faction** >= Indifferent then



>**Vacto Molunel says:** Piqued your interest, did I?  Well, you see, I am one of the few dwarves who possess the knowledge and talent to craft a unique type of armor entirely out of scarab carapaces.  While my specialty is making [scarab helms]. I have also been convinced to make [scarab breastplates] and [scarab boots] from time to time.  All of the pieces I craft are to dwarven proportions, but I have had some gnomish and halfling customers as well.  They come from all over for my armor.


else



>**Vacto Molunel says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `scarab helms`



if **Faction** >= Indifferent then



>**Vacto Molunel says:** Interested in a scarab helm, are you?  Well, because my talent is so unique and my time is so valuable, I am afraid I could only make you a helm if you were to provide me with the two scarab carapaces necessary to accommodate a head such as yours.  I will also need a payment of 5 gold pieces.  The Butcherblocks are crawling with worker scarabs that have just the right size carapaces for our needs.


else



>**Vacto Molunel says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `scarab breastplates`



if **Faction** >= Amiable then



>**Vacto Molunel says:** Ah..  A  scarab breastplate.. hmm.  Well, if you want to convince me to go though the trouble of crafting one of those, not only will you have to pay my fee of 23 gold pieces, you must provide me with a pristine giant scarab carapace.  I refuse to make a breastplate with cracked carapaces.


elseif( **Faction is** == Indifferent) then



>**Vacto Molunel says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Vacto Molunel says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `scarab boots`



if **Faction** >= Amiable then



>**Vacto Molunel says:** Ah..  Scarab Boots.. hmm.  Well, if you want to convince me to go though the trouble of crafting a pair of those, not only will you have to pay my fee of 17 gold pieces, you must provide me with a cracked giant scarab shell and 2 scarab legs.


elseif( **Faction is** == Indifferent) then



>**Vacto Molunel says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Vacto Molunel says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `irontoe`



>**Vacto Molunel says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Vacto Molunel says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `trondle`



>**Vacto Molunel says:** Trondle Ogrebane is the legendary dwarven warrior who single-handedly exterminated the ogre clan called the [Mudtoes]. He was recently killed in battle. It took an entire legion of Crushbone orcs to bring him down. Furtog is still fuming about that.

**You say:** `mudtoes`



>**Vacto Molunel says:** The Mudtoes were a small clan of ogres. They lived somewhere in the Butcherblock Mountains. They had an insatiable appetite for dwarves. They were finally destroyed by the hand of Trondle Ogrebane.

**You say:** `crushbone orc`



>**Vacto Molunel says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `battle of busted skull`



>**Vacto Molunel says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end

## Turn-Ins



local text1 = "Well, that is one of the items I need to make scarab boots. Do you have the rest?";

local text2 = "This is good, but in order to finish the job, I need both a pristine giant scarab carapace and 23 gold.";

local text3 = "Remember, for the scarab helm I require you give me two scarab carapaces as well as 5 gold.";



if **Faction** >= Indifferent and  **You turn in:** [Scarab Carapace](/item/13849), [Scarab Carapace](/item/13849), gold = 4


>**Vacto Molunel says:** Excellent. Here is your helm. Wear it with pride! And be sure to occasionally wipe out the insulating mucus that tends to build up on its underside. It will make your hair fall out. One more thing, would you be interested in [scarab boots] to match your helm?


* __Faction:__ [Storm Guard](/faction/312) (2)


* __Faction:__ [Kazon Stormhammer](/faction/274) (1)


* __Faction:__ [Miners Guild 249](/faction/293) (1)


* __Faction:__ [Merchants of Kaladim](/faction/290) (1)


* __Faction:__ [Craknek Warriors](/faction/232) (-1)



 **You receive:**  [Small Scarab Helm](/item/2175) (+500 exp)

if **Faction** >= Amiable and  **You turn in:** [Pristine Giant Scarab Carapace](/item/13133), gold = 22


>**Vacto Molunel says:** If I do say so myself, this is one of the finest breastplates in all of Norrath. I am truly a master at my craft. You might want to wipe out some of the excess scarab goo before wearing it, though.


* __Faction:__ [Storm Guard](/faction/312) (5)


* __Faction:__ [Kazon Stormhammer](/faction/274) (1)


* __Faction:__ [Miners Guild 249](/faction/293) (1)


* __Faction:__ [Merchants of Kaladim](/faction/290) (1)


* __Faction:__ [Craknek Warriors](/faction/232) (-1)



 **You receive:**  [Small Scarab Breastplate](/item/2176) (+5000 exp)

if **Faction** >= Amiable and  **You turn in:** [Cracked Giant Scarab Carapace](/item/13132), [Scarab Legs](/item/13848), [Scarab Legs](/item/13848), gold = 16


>**Vacto Molunel says:** Very good! Let me see here. Thread the legs around like this and... There you go. Wear them with pride!


* __Faction:__ [Storm Guard](/faction/312) (3)


* __Faction:__ [Kazon Stormhammer](/faction/274) (1)


* __Faction:__ [Miners Guild 249](/faction/293) (1)


* __Faction:__ [Merchants of Kaladim](/faction/290) (1)


* __Faction:__ [Craknek Warriors](/faction/232) (-1)



 **You receive:**  [Small Scarab Boots](/item/2177) (+5000 exp)

**This NPC *should* return incorrect items given.**





