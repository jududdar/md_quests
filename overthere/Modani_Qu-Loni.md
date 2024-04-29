# Modani Qu-Loni

## Dialog

**You say:** `hail`



>**Modani Qu-Loni says:** The hidden self inside a myriad of magic is one that walks quite softly. Yes, that is what you must seek.

**You say:** `ready`



>**Modani Qu-Loni says:** Scattered throughout the world are various items. To prove your worth, go collect these and return them to me. The Xolion Rod, Innoruuk's Word, Chalice of Kings, and snow blossoms.

**You say:** `chalice of kings`



>**Modani Qu-Loni says:** The Chalice of Kings is the chalice of elven kings. Previously thought to be lost to the ages, it was recently discovered. I need its magical powers to create a magical liquid.

**You say:** `xolion rod`



>**Modani Qu-Loni says:** This is the rod of an ancient civilization found on this continent. Nothing is known of it other than that the scaled ones discovered it years ago.

**You say:** `snow blossoms`



>**Modani Qu-Loni says:** These are flowers that are also used in the creation process. They were once widespread, but now I am told they only grow in select places.

**You say:** `innoruuks word`



>**Modani Qu-Loni says:** The strict doctrine of the priests of Innoruuk is used as a material component in the crafting. The power of their hate must not be underestimated.

**You say:** `sack`



>**Modani Qu-Loni says:** Before I provide the item, you must show me that you have spoken to Jeb.
end

## Turn-Ins





if( **You turn in:** [Jeb's Seal](/item/10604)) then 


>**Modani Qu-Loni says:** Ah yes, Jeb's seal. The time to craft a Serpent must have come. I will need components collected to craft the first of the pieces. I will also provide you with a sack in which you must combine the items. Are you ready to collect them?


 **You receive:** GiveAll( [An Enchanters Sack](/item/17861), [Jeb's Seal](/item/10604)) 

elseif( **You turn in:** [A Sack For Modani](/item/10635)) then


>**Modani Qu-Loni says:** Excellent, you have done well. Here is the first piece of the staff. Now you must go seek out the second master; he will clear the path for you.


* __Faction:__ [Truespirit](/faction/404) (100)


 **You receive:**  [1st Piece of Staff](/item/10610) (+100000 exp)

**This NPC *should* return incorrect items given.**





