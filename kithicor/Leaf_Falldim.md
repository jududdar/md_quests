# Leaf Falldim
## Dialog

**You say:** `hail`



>**Leaf Falldim says:** Greetings. Soandso!  Respect the woods and all its inhabitants or face the wrath of the rangers.  Do notup like [Maldyn Greenburn].

**You say:** `maldyn greenburn`



>**Leaf Falldim says:** Maldyn was once one of us.  He was the finest of archers.  Everyone aspired to be like him.  He soon was tempted to hunt.  The animals of these woods found themselves nothing more than moving targets for Maldyn's training.  We held a trial and exiled him to parts unknown.  He would take with him Morin's [Bow of Kithicor].  I was asked to find a worthy ranger to [retrieve the bow].

**You say:** `bow of kithicor`



>**Leaf Falldim says:** The Bow of Kithicor was carved from an ancient tree. It has great powers which were but a portion of the tree's mana. I seek a brave ranger to [retrieve the bow].

**You say:** `retrieve the bow`



>**Leaf Falldim says:** Search the lands of the Unkempt Druids in the Rathe Mountains.  I have heard of his arrows being found inside its territories and  of his death wish to hunt down its leader.  Retrieve the bow and return it to me and I shall give you the ivy etched gauntlets.

**You say:** `ivy etched legging`



>**Leaf Falldim says:** 'I will make you an offer. If you be a ranger, as they are made for only a ranger, you must venture to Faydwer. There you shall seek out Lieutenant Leafstalker of the Kelethin army. He sent a message of his retrieval of the Quiver of Kithicor. Tell him you want it and return it to me. Oh... and one more [small item].

**You say:** `small item`



>**Leaf Falldim says:** Along with the quiver you shall journey to Erudin and purchase a Star of Odus gem to add to the quiver. Consider the coins you shall spend an offering to the woods.

**You say:** `ivy etched boot`



>**Leaf Falldim says:** 'If you wish the ivy etched boots, you shall do me a favor. I am testing new arrow tips and wish a few of the hardest minerals I know of. From the mines of the Temple of Solusek Ro, ronium. From the land of Mistmoore, fetch me Mistmoore granite. Return these to me along with a guild offering of 2000 gold pieces.
end

## Turn-Ins



local text1 = "I asked for a guild donation of 2000 gold coins, Mistmoore granite and a bar of ronium.";


local text2 = "This is but a portion of the bow. I must have the other part.";



if **You turn in:** [Broken Bow Part B](/item/12321), [Broken Bow Part A](/item/12320)


>**Leaf Falldim says:** You have performed well, brave ranger. Put these upon your hands. Protection from the strongest of bowstring and magic are their greatest power. I do believe we have another mission which may yield you the [ivy etched leggings].


* __Faction:__ [Kithicor Residents](/faction/269) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


 **You receive:**  [Ivy Etched Gauntlets](/item/3190) (+10000 exp)

elseif **You turn in:** [Star of Odus](/item/10059), [Quiver of Kithicor - full](/item/12328)


>**Leaf Falldim says:** Wonderful!! I see he did find it. How lucky we are that he did all the hard work. My thanks to you are embodied in these ivy etched leggings. Now you may [earn the ivy etched boots] to go along with them.


* __Faction:__ [Kithicor Residents](/faction/269) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


 **You receive:**  [Ivy Etched Leggings](/item/3191) (+10000 exp)

elseif **You turn in:** [A Bar of Ronium](/item/12305), [Mistmoore Granite](/item/12306),gold = 1000


>**Leaf Falldim says:** You have succeeded!! I believe I owe you the ivy etched boots.


* __Faction:__ [Kithicor Residents](/faction/269) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


 **You receive:**  [Ivy Etched Boots](/item/3192) (+10000 exp)

**This NPC *should* return incorrect items given.**






