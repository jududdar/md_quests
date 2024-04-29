# Hogunk Ventille
## Dialog

**You say:** `Hail`



>**Hogunk Ventille says:** Hail. and welcome to Stormguard Hall. home to all great warriors! Are you also a [warrior of the Stormguard] or do you [follow another guild]?

**You say:** `i am a warrior of the stormguard`



if **Faction** >= Amiable then



>**Hogunk Ventille says:** As I thought. You do not appear to be one who relies on wits rather than brawn. no offense. I have word that a Stormguard on duty has deserted his post at one of the guardposts in the Butcherblocks. I want you to go and seek him out. He is Guard Bundin. Return his Stormguard axe to me. along with his head. There shall be no cowards in the Stormguard!!


elseif( **Faction is** == Indifferent) then



>**Hogunk Ventille says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Hogunk Ventille says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `i follow another guild`



>**Hogunk Ventille says:** Then go to your guild. This is the hall of the dwarven warriors - not a place for common folk to lounge around.

**You say:** `irontoe`



>**Hogunk Ventille says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Hogunk Ventille says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `trondle`



>**Hogunk Ventille says:** Trondle Ogrebane is the legendary dwarven warrior who single-handedly exterminated the ogre clan called the [Mudtoes]. He was recently killed in battle. It took an entire legion of Crushbone orcs to bring him down. Furtog is still fuming about that.

**You say:** `mudtoes`



>**Hogunk Ventille says:** The Mudtoes were a small clan of ogres. They lived somewhere in the Butcherblock Mountains. They had an insatiable appetite for dwarves. They were finally destroyed by the hand of Trondle Ogrebane.

**You say:** `crushbone orc`



>**Hogunk Ventille says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `battle of busted skull`



>**Hogunk Ventille says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end

## Turn-Ins



local text = "Aren't you forgetting something? I instructed you to return with Guard Bundin's Head and his Stormguard axe.";



if **Faction** >= Amiable and  **You turn in:** [Dwarf Head](/item/12156), [Rusty Axe](/item/5014)) then


>**Hogunk Ventille says:** I shall display this in the guard hall. Let it be a warning to all those who dare to run from battle. As for you, that was splendid work, but next time, remember to wrap decapitated heads in something drip-proof. Those stains will never come out! Oh yes, and here is your reward.


* __Faction:__ [Kazon Stormhammer](/faction/274) (2)


* __Faction:__ [Storm Guard](/faction/312) (15)


* __Faction:__ [Miners Guild 249](/faction/293) (2)


* __Faction:__ [Kaladim Merchants](/faction/5025) (3)


* __Faction:__ [Craknek Warriors](/faction/232) (-3)


 **You receive:** eq.ChooseRandom( [Bronze Long Sword](/item/5027), [Bronze Scimitar](/item/5034), [Bronze Mace](/item/6019), [Bronze Morning Star](/item/6024), [Bronze Rapier](/item/7013), [Cracked Staff](/item/6018), [Tarnished Two Handed Sword](/item/5070), [Tarnished Two Handed Battle Axe](/item/5071), [Fine Steel Morning Star](/item/6351)) (+5000 exp)

**This NPC *should* return incorrect items given.**
