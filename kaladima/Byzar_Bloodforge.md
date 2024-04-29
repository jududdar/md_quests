# Byzar Bloodforge



## Dialog

**You say:** `hail`



>**Byzar Bloodforge says:** State your business!!  I have no time for chitchat.  Well..  speak up. toad!!  What?!!..  Have you come here to [return goblin beads]?

**You say:** `return goblin beads`



>**Byzar Bloodforge says:** If you wish to return Runnyeye Warbeads you best have at least four of them.  Do not waste my time with any less.  If I am in a good mood I just may reward you with some trash, err..  I mean equipment from our armory.

**You say:** `Zarchoomi`




>**Byzar Bloodforge says:** Do not speak the names of Zarchoomi and Corflunk!!  I have heard enough of those ogres!!  I would pay greatly for their heads!!

**You say:** `take a little trip`



if **Faction** >= Amiable then



>**Byzar Bloodforge says:** Yes.  You will do.  My sister was once engaged to a fellow warrior.  He disgraced her and left her crying at the altar.  I will have his head for such a slap in the face of my family.  His name was Trumpy Irontoe, once a member of the now defunct Irontoe Brigade.  I know not where he went.  Find his whereabouts and return his head to me.  Do so, and I shall make you an honorary member of the Bloodforge Brigade.


elseif **Faction** >= Indifferent then



>**Byzar Bloodforge says:** Prove yourself to the Stormguard and then we shall talk.  Perhaps you may assist Master Canloe and show your worth to us.


else



>**Byzar Bloodforge says:** Your shifty eyes tell me that you are no ally of the Stormguard.


**You say:** `irontoe`



>**Byzar Bloodforge says:** The Irontoe Brigade was formed by Drumpy Irontoe. It was once the finest band of warriors in Kaladim. They were the elite branch of the Stormguard. King Kazon sent them on a mission to the lands of the Crushbone orcs. At the Battle of Busted Skull they met their fate.

**You say:** `tumpy`



>**Byzar Bloodforge says:** If you frequent the pubs, you just may run into Tumpy Irontoe. He was once the brave leader of the Irontoe Brigade. Whatever you do, do not mention the Battle of Busted Skull. I am sure that would bring back some bad memories for him.

**You say:** `trondle`



>**Byzar Bloodforge says:** Trondle Ogrebane is the legendary dwarven warrior who single-handedly exterminated the ogre clan called the [Mudtoes]. He was recently killed in battle. It took an entire legion of Crushbone orcs to bring him down. Furtog is still fuming about that.

**You say:** `mudtoes`



>**Byzar Bloodforge says:** The Mudtoes were a small clan of ogres. They lived somewhere in the Butcherblock Mountains. They had an insatiable appetite for dwarves. They were finally destroyed by the hand of Trondle Ogrebane.

**You say:** `crushbone orc`



>**Byzar Bloodforge says:** The army of the Crushbone orcs is deadly indeed. They are great military strategists. It was a legion of them that brought down the great [Trondle Ogrebane]. Speak with Furtog Ogrebane about the Crushbones. He has need of warriors such as you.

**You say:** `battle of busted skull`



>**Byzar Bloodforge says:** The Battle of Busted Skull was fought in the land of the Crushbone orcs.  King Kazon sent the entire Irontoe Brigade to retrieve an ancient artifact from an old dwarven outpost.  The battle was fierce.  At its only a handful of Irontoes made it back.  After that, the Irontoe Brigade survivors left Kaladim for good.  All except Tumpy Irontoe.
end

## Turn-Ins



local text = "What good is one?! I called for the heads of both Corflunk and Zarchoomi!";



if( **You turn in:** [RunnyEye Warbeads](/item/13931), [RunnyEye Warbeads](/item/13931), [RunnyEye Warbeads](/item/13931), [RunnyEye Warbeads](/item/13931)) then


>**Byzar Bloodforge says:** You finally have proven yourself a warrior, a slow one!!  Take this reward and ask for nothing else.  You should be proud to defend Kaladim and expect no reward.


* __Faction:__ [Storm Guard](/faction/312) (5)


* __Faction:__ [Kazon Stormhammer](/faction/274) (1)


* __Faction:__ [Miners Guild 249](/faction/293) (1)


* __Faction:__ [Merchants of Kaladim](/faction/290) (1)


* __Faction:__ [Craknek Warriors](/faction/232) (-1)


 **You receive:** eq.ChooseRandom( [Small Tattered Skullcap](/item/2113), [Small Tattered Mask](/item/2114), [Small Tattered Gorget](/item/2115), [Small Patchwork Tunic](/item/2116), [Small Tattered Shoulderpads](/item/2117), [Small Patchwork Cloak](/item/2118), [Small Tattered Belt](/item/2119), [Small Patchwork Sleeves](/item/2120), [Small Tattered Wristbands](/item/2121), [Small Tattered Gloves](/item/2122)) (+1000 exp)

elseif **Faction** >= Apprehensive and  **You turn in:** [Ogre Head](/item/13741), [Ogre Head](/item/13740)) then


>**Byzar Bloodforge says:** I underestimated you.  You are truly a great warrior.  I reward you with a piece of my own Bloodforge armor.  You would be fine Bloodforge Brigade material!  How would you like to [take a little trip] in the name of the Bloodforge Brigade?


* __Faction:__ [Storm Guard](/faction/312) (20)


* __Faction:__ [Kazon Stormhammer](/faction/274) (3)


* __Faction:__ [Miners Guild 249](/faction/293) (3)


* __Faction:__ [Merchants of Kaladim](/faction/290) (5)


* __Faction:__ [Craknek Warriors](/faction/232) (-5)


 **You receive:** eq.ChooseRandom( [Bloodforge Helm](/item/3090), [Bloodforge Mail](/item/3091), [Bloodforge Armplates](/item/3092), [Bloodforge Bracers](/item/3093), [Bloodforge Gauntlets](/item/3094), [Bloodforge Legplates](/item/3095), [Bloodforge Boots](/item/3096)) (+1000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Dwarf Head](/item/12136)) then


>**Byzar Bloodforge says:** Ha!! His death brings me great happiness.  I owe you much.  Take this hammer.  It is the hammer of the Bloodforge Brigade.  May it serve you well.  Now go, so I can enjoy this moment of happiness alone.


* __Faction:__ [Storm Guard](/faction/312) (5)


* __Faction:__ [Kazon Stormhammer](/faction/274) (1)


* __Faction:__ [Miners Guild 249](/faction/293) (1)


* __Faction:__ [Merchants of Kaladim](/faction/290) (1)


* __Faction:__ [Craknek Warriors](/faction/232) (-1)


 **You receive:**  [Bloodforge Hammer](/item/13314) (+10000 exp)

**This NPC *should* return incorrect items given.**
