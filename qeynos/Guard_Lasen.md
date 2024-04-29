# Guard Lasen
## Dialog

**You say:** `hail`



>**Guard Lasen says:** Greetings, Soandso! Whew! I sure get parched out here on patrol. Even when it rains I can't help but build up a [thirst] defending the good people of Qeynos.

**You say:** `drink`



>**Guard Lasen says:** Well, I have a bit of a belly sickness so the only thing I can drink is normal water.  I can't even keep down the stuff our local magicians summon and call water. If you would bring me a water flask, I would be most grateful.

**You say:** `weapon`



>**Guard Lasen says:** This city has been blessed with the craftsmanship of the Ironforges.  Their weapons are supreme.  Their shop can be found near the Temple of Life in North Qeynos.  You may also try the local warrior guild.

**You say:** `order of the three`



>**Guard Lasen says:** The Order of Three consists of the three positive circles of the arcane known as magic, enchantment and wizardry.  This guild keeps very busy in its hall near the arena.  All in Qeynos respect their powers.

**You say:** `monk guild`



>**Guard Lasen says:** In North Qeynos sits the house of the Silent Fist Clan.  These monks are welcome in Qeynos and often assist in training the Qeynos Guard in hand to hand combat.

**You say:** `bank`



>**Guard Lasen says:** Qeynos Hold in South Qeynos is just across from the arena.  You know, over the bridge behind Firepride's.

**You say:** `port`



>**Guard Lasen says:** The port of Qeynos is located in South Qeynos.  From here one may catch the ship to Erudin.

**You say:** `kane`



>**Guard Lasen says:** Commander Kane Bayle is the commander of all the Qeynos Guard.  He is second only to his brother, Antonius Bayle.  His post is in the guard house at the city gates.  Mind you, do not bother him, he has a bit of a temper.

**You say:** `circle.* unseen hand`



>**Guard Lasen says:** The Circle of the Unseen Hand?  I have heard nothing of them.  Are they some sort of performing magic troupe?

**You say:** `paladin guild`



>**Guard Lasen says:** Within Qeynos are the Knights of Thunder and the Priests of Life.  Both of these orders consist of clerics and paladins and are respected by all.  The Hall of Thunder lies in South Qeynos and the Temple of Life is in North Qeynos.

**You say:** `necromancer guild`



>**Guard Lasen says:** What gibberish are you spouting?  There is not, nor will there ever be, such an organization as that within a hundred miles of Qeynos, not with the Qeynos Guard on patrol.  Next you will be inquiring of a rogue guild!  Really!

**You say:** `ranger guild`




>**Guard Lasen says:** I believe you shall find the Protectors of the Pine and Jaggedpine Treefolk in the hollow of Surefall Glade.


**You say:** `jaggedpine treefolk`



>**Guard Lasen says:** In Surefall Glade there are druids called the Jaggedpine Treefolk.  These men and women often assist our army during times of war.

**You say:** `linarius`



>**Guard Lasen says:** The Qeynos Tower Guards of the hills and plains are commanded by Captain Linarius Graffe.  He often has much to report.  He is posted in a keep which spans a river.  I believe it is in the northern Plains of Karana.

**You say:** `north qeynos`



>**Guard Lasen says:** The passages to North Qeynos can be found near the bard's guild or next to the Clock of Ak'Anon.

**You say:** `inn`




>**Guard Lasen says:** If you need a place to rest, I highly recommend the Lion's Mane Inn and Tavern.  Poor adventurers all huddle together in one of the backrooms of Fish's.



**You say:** `antonius`



>**Guard Lasen says:** Antonius Bayle is the ruler of Qeynos. He is such a great man that they renamed this continent after him. He brought Qeynos to the glory it now is. He formed the mightest army on Norrath, the Qeynos Guard. It is through his guidance that we shall protect all nations of Antonica from any evil threat. He does not venture into the city streets often. He is quite busy.

**You say:** `tillin`



>**Guard Lasen says:** Captain Tillin Brightblade is the commander of the Qeynos City Guard. Extermination of the Sabertooths is his paramount concern. He has recently begun to hire mercenaries to assist in the extermination. If you wish to help out then go and speak with him. He is most often found discussing tactics with Ebon Strongbear at arena.

**You say:** `saber`



>**Guard Lasen says:** What was that you said? You mentioned the Sabertooths of Blackburrow? Those gnolls have caused this city trouble harm for too long. We have yet to force them from Qeynos Hills. I hear rumors of a few merchants who even dare to sell the outland Blackburrow Stout which is brewed by the gnolls. Foolish!! We call upon all citizens to assist in ridding our land of the gnolls. If you wish to join the fight then speak with Captain Tillin.
end

## Turn-Ins



if( **You turn in:** [Water Flask](/item/13006)) then


>**Guard Lasen says:** Oh, thank you so much!' Lasen brings the drink to his lips and ravenously drinks the bottle's entire contents, ' Aaaaah. Here, please take this reward for your kindness.  Also take my advice, do not go exploring beneath Qeynos unless you bring friends.  I have seen too many like you enter the aqueducts alone, never to return.


e.other:SendSound(141);


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Antonius Bayle](/faction/219) (1)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [Merchants of Qeynos](/faction/291) (1)


e.other:GiveCash(math.random(5),0,0,0);

local returned = item_lib.return_items(e.self, e.other, e.trade, false)

if ( returned ) then


>**Guard Lasen says:** Thank you, I guess. But did you not hear what it is I am thirsty for?
end
