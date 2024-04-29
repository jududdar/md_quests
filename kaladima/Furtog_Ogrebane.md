# Furtog Ogrebane
## Dialog

**You say:** `hail`



>**Furtog Ogrebane says:** Hail, mighty Soandso! Welcome to Stormguard Hall. I am Captain Furtog Ogrebane, only surviving descendant of the legendary Trondle Ogrebane, slayer of the [Mudtoes]. If you wish to serve the grand city of Kaladim. I urge you to speak with any of the trainers. Good day.

**You say:** `mudtoes`



>**Furtog Ogrebane says:** The Mudtoes were a small but mighty clan of ogres. My great father [Trondle] destroyed them. I have heard disturbing rumors of one Mudtoe surviving. Would you mind [searching for the Mudtoes] or have you other duties to perform?

**You say:** `trondle`



>**Furtog Ogrebane says:** Trondle was my great father and slayer of the Mudtoes. He was killed by those vile Crushbone orcs. If you truly wish to help Kaladim remain safe. speak with trainer Canloe Nusback. Say that you are ready to serve Kaladim.

**You say:** `searching`



>**Furtog Ogrebane says:** I have heard persistent rumors of two Mudtoe ogres who survived the slaughter.  Go to the port of Butcherblock.  Those dock hands must have heard of the name [Mudtoe].  Bring me the remaining heads of the Mudtoes!!  I want all the Mudtoes dead!!  Do not return until you have them both!!

**You say:** `irontoe`



>**Furtog Ogrebane says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Furtog Ogrebane says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `crushbone orc`



>**Furtog Ogrebane says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `battle of busted skull`



>**Furtog Ogrebane says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end

## Turn-Ins



local text = "There is another! I have reports that there were two Mudtoe ogres on the island chain in the Ocean of Tears. I want both heads!";



if( **You turn in:** [Recruitment Letter](/item/18766)) then 


>**Furtog Ogrebane says:** Greetings, friend, and welcome to Stormguard Hall! I am Furtog Ogrebane, Captain of the Guard. We shall train you to be a fearless warrior, who will serve and protect King Kazon well. Here is your tunic.  Now, let's begin your training.


* __Faction:__ [Storm Guard](/faction/312) (100)


* __Faction:__ [Kazon Stormhammer](/faction/274) (15)


* __Faction:__ [Miners Guild 249](/faction/293) (15)


* __Faction:__ [Merchants of Kaladim](/faction/290) (25)


* __Faction:__ [Craknek Warriors](/faction/232) (-25)


 **You receive:**  [Dirt Stained Tunic*](/item/13515) (+20 exp)

elseif( **You turn in:** [Ogre Head](/item/13316), [Ogre Head](/item/13317)) then 


>**Furtog Ogrebane says:** Finally my great father's work has been completed. All the Mudtoe ogres have been exterminated. Thank you. Take this weapon which my father pried from the cold, dead hands of the Mudtoe ogre captain. It is called an ogre war maul. May you wield it with honor in the name of Kaladim.





* __Faction:__ [Storm Guard](/faction/312) (50)


* __Faction:__ [Kazon Stormhammer](/faction/274) (7)


* __Faction:__ [Miners Guild 249](/faction/293) (7)


* __Faction:__ [Merchants of Kaladim](/faction/290) (12)


* __Faction:__ [Craknek Warriors](/faction/232) (-12)


 **You receive:**  [Ogre War Maul](/item/6302) (+250 exp)

**This NPC *should* return incorrect items given.**
