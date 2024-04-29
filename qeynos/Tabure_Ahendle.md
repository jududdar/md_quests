# Tabure Ahendle
## Dialog

**You say:** `hail`



>**Tabure Ahendle says:** What have we here?  Perhaps a future Ebon Strongbear?  A [member of the Steel Warriors]?  If the way of the warrior is not to your liking, might I suggest joining the League of Antonican Bards?  The only damage you might take there is a sore throat! HAHAHA!

**You say:** `steel warrior`



if **Faction** >= Amiable then



>**Tabure Ahendle says:** A warrior, you say?  I have never met you.  You must be from the [bunker] or perhaps just a new recruit.  You should test your skills with Brin Stolunger.  When you have done that, then, maybe you could [assist] me.


elseif **Faction** >= Indifferent then








>**Tabure Ahendle says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Tabure Ahendle says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


**You say:** `assist`



if **Faction** >= Amiable then



>**Tabure Ahendle says:** So, you think you be of assistance to me? Let me test your skill. Travel to Erudin and seek out the beasts which are called Kobolds. I have never seen one and would very much like to have four Kobold Hides with which to make a rug. To do so would earn you some barely used rawhide armor - maybe even a shield.


elseif **Faction** >= Indifferent then








>**Tabure Ahendle says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Tabure Ahendle says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


**You say:** `dangerous task`



if **Faction** >= Amiable then



>**Tabure Ahendle says:** A ship sank while returning from Odus. On this ship was my squire, Tombor. He sank to the bottom and there he still lies. With him went a map. I would very much like you to search for this sunken ship. Return the map to me. I am sure it is still in the rotting hands of Tombor.









elseif **Faction** >= Indifferent then








>**Tabure Ahendle says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Tabure Ahendle says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!


**You say:** `bunker`



if **Faction** >= Amiable then



>**Tabure Ahendle says:** Far to the eastern coast of Antonica lies the great trade city of Freeport.  It is there that our second chapter of Steel Warriors has built the arena called the bunker.




elseif **Faction** >= Indifferent then








>**Tabure Ahendle says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Tabure Ahendle says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!

end

## Turn-Ins



local text = "I believe I stated that I need four kobold hides to make a rug.";


if( **Faction is** >= Amiable and  **You turn in:** [A Blurred Map](/item/13423)) then 


>**Tabure Ahendle says:** The map!! It is all blurred. The ink has run. I shall never be able to decipher it now. Still, I owe you for completion of your mission. May these be of assistance. It is always good for a warrior to be well supplied.





* __Faction:__ [Steel Warriors](/faction/311) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Knights of Truth](/faction/281) (1)


 **You receive:** eq.ChooseRandom( [Cast-Iron Long Sword](/item/5082), [Buckler](/item/9001), [Rusty Halberd](/item/5024)) (+5000 exp)

elseif( **Faction is** >= Amiable and  **You turn in:** [Kobold Hide](/item/13424), [Kobold Hide](/item/13424), [Kobold Hide](/item/13424), [Kobold Hide](/item/13424)) then


>**Tabure Ahendle says:** Incredible!! Such grand tones. It shall make a fine rug. You have shown me that you cannot always judge a book by its cover. You are quite skilled. Would you like to perform a [dangerous task] for me?





* __Faction:__ [Steel Warriors](/faction/311) (20)


* __Faction:__ [Guards of Qeynos](/faction/262) (4)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-3)


* __Faction:__ [The Freeport Militia](/faction/330) (-3)


* __Faction:__ [Knights of Truth](/faction/281) (4)


 **You receive:** eq.ChooseRandom( [Raw-hide Tunic](/item/2140), [Raw-hide Leggings](/item/2147), [Round Shield](/item/9002)) (+5000 exp)

**This NPC *should* return incorrect items given.**


