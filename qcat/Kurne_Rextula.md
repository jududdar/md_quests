# Kurne Rextula
## Dialog

**You say:** `hail`



>**Kurne Rextula says:** Welcome to the new order of life, the life of service to our diseased Lord, Bertoxxulous. Did you encounter any of my [pets] on the way here? I hope not.

**You say:** `pets`



>**Kurne Rextula says:** My pets are the skeleton guardians of these catacombs. Some have been behaving erratically since the arrival of [Drosco].

**You say:** `drosco`



>**Kurne Rextula says:** Drosco used to be a loyal member of our shrine, until we learned the truth. The truth was that he was a mole from the Knights of Thunder. It appears they are assisting the Temple of Life in their pursuit of our eradication. Drosco was apprehended and boiled alive. I turned his boiled body into a zombie to march these halls. Now he must be stopped. He has begun to [compromise the shrine's location].

**You say:** `compromise`



if **Faction** >= Amiable then



>**Kurne Rextula says:** The problem is, he was strong in Karana's faith. And as sometimes is the case, there is a resonance from his deity. This causes him to wander in and out of our hidden shrine and I believe it also interferes with my control of the other pets. Please find him and destroy him. Bring me back the note I placed upon his body. Go!!


elseif **Faction** >= Indifferent then



>**Kurne Rextula says:** While the Bloodsabers appreciate your past contributions to Bertoxxulous and our cause, we do not feel you can be trusted with vital information yet.


else



>**Kurne Rextula says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `new task`



if **Faction** >= Amiable then



>**Kurne Rextula says:** I have been working with a man named Lord Grimrot. We are attempting to raise an army of undead in the Plains of Karana. When the time is right, we shall attack from within as well as from beyond the walls of Qeynos. This army needs one more commander. I must find a Bloodsaber to [retrieve the commander].


elseif **Faction** >= Indifferent then



>**Kurne Rextula says:** While the Bloodsabers appreciate your past contributions to Bertoxxulous and our cause, we do not feel you can be trusted with vital information yet.


else



>**Kurne Rextula says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `retrieve the commander`



if **Faction** >= Amiable then



>**Kurne Rextula says:** I have searched for the appropriate man... Sir Lucan of Freeport, Field Marshal Ralem, Marshal Anrey of Rivervale, even Commander Kane Bayle. Any of them would do, but they are either inaccessible or share a common goal with us. So I have decided Trumpy Irontoe is the one. Any former member of the [Irontoe Brigade] has a wealth of military strategies. Kill him and bring me his head. Kane will not be pleased, but, it must be done.


elseif **Faction** >= Indifferent then



>**Kurne Rextula says:** While the Bloodsabers appreciate your past contributions to Bertoxxulous and our cause, we do not feel you can be trusted with vital information yet.


else



>**Kurne Rextula says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `Irontoe Brigade`



if **Faction** >= Amiable then



>**Kurne Rextula says:** The Irontoe Brigade was a legendary military unit hailing from the dwarven city of Kaladim. After a dangerous assault, where more than three quarters of the unit met their bloody fate, the brigade disbanded and left for parts unknown. In Fish's Bar, in Qeynos, you can find one of them, Trumpy Irontoe.


elseif **Faction** >= Indifferent then



>**Kurne Rextula says:** While the Bloodsabers appreciate your past contributions to Bertoxxulous and our cause, we do not feel you can be trusted with vital information yet.


else



>**Kurne Rextula says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!


end

## Turn-Ins



if **Faction** >= Amiable and  **You turn in:** [A Sealed Letter](/item/18805)) then


>**Kurne Rextula says:** Good work! You shall rise quickly in our ranks of evil. Let no man stand in your way and never betray the shrine or you to will join our collection of undead. You can also assist me with a [new task].


* __Faction:__ [Bloodsabers](/faction/221) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:** eq.ChooseRandom( [Belt Pouch](/item/17002), [Spell: Siphon Strength](/item/15343)) (+1000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Dwarf Head](/item/12136)) then


>**Kurne Rextula says:** Incredible!! You have slain one of the greatest warriors in Qeynos!! He must have been full of grog. No doubt he drank most of his skill away. Now I shall cast a spell and strip the flesh from his skull and.. Presto!! Take this skull to Lord Grimrot somewhere in the Plains of Karana. He will be in the center of a field of skeletons. If he is not there, wait for his return. He must return eventually.


* __Faction:__ [Bloodsabers](/faction/221) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:**  [Dwarf Skull](/item/12137) (+1000 exp)

elseif( **Faction is** < Amiable) then


>**Kurne Rextula says:** I'm... erm, not quite sure what to do with this, but... thanks, I guess.

item_lib.return_items(e.self, e.other, e.trade, false);