# Torgon Blademaster
## Dialog

**You say:** `hail`



>**Torgon Blademaster says:** Greetings, Soandso. Are you a [true warrior]?

**You say:** `true warrior`



>**Torgon Blademaster says:** Then you shall be tested as one. Choose. Do you wish to be tested by Falorn or Ogog?

**You say:** `falorn`



>**Torgon Blademaster says:** So be it, warrior.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the mighty warrior Falorn to test you.


**You receive:**  [Falorn story](/item/18520)

**You say:** `ogog`



>**Torgon Blademaster says:** Ogog?  You are indeed brave for choosing that brute.  Take this book telling the tale of Ogog and read it.  When you are finished, hand it back to me.


**You receive:**  [Ogog Story](/item/18521)
end


## Turn-Ins



if( **You turn in:** [Falorn story](/item/18520)) then 



>**Torgon Blademaster says:** Falorn, come forth!


**Spawn NPC:**  [Falorn](/npc/71067) at (**y:** 1392.4, **x:** 563.3)


**Torgon Blademaster despawns.**

elseif( **You turn in:** [Ogog Story](/item/18521)) then 


>**Torgon Blademaster says:** Farewell.


**Spawn NPC:**  [Ogog](/npc/71064) at (**y:** 1392.4, **x:** 563.3)


**Torgon Blademaster despawns.**

**This NPC *should* return incorrect items given.**


