# Wizard Schrock
## Dialog

**You say:** `hail`



>**Wizard Schrock says:** Greetings, Soandso. Do you believe that you are a [great Wizard]?

**You say:** `great wizard`



>**Wizard Schrock says:** I will not take your word for it! You must prove your greatness to my apprentices. Do you wish to be tested by Neasin or by Abec?

**You say:** `Neasin`



>**Wizard Schrock says:** Neasin it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the mighty wizard Neasin to test you.


**You receive:**  [Fire and Ice](/item/18530)

**You say:** `Abec`



>**Wizard Schrock says:** Abec it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the mighty wizard Abec to test you.


**You receive:**  [Knowledge and Power](/item/18531)
end


## Turn-Ins



if( **You turn in:** [Fire and Ice](/item/18530)) then 


>**Wizard Schrock says:** Till next time!  Farewell!


**Spawn NPC:**  [Neasin Leornic](/npc/71092) at (**y:** 1304.3, **x:** 585)


**Wizard Schrock despawns.**

elseif( **You turn in:** [Knowledge and Power](/item/18531)) then 


>**Wizard Schrock says:** Till next time!  Farewell!


**Spawn NPC:**  [Abec Ianor](/npc/71079) at (**y:** 1304.3, **x:** 585)


**Wizard Schrock despawns.**

**This NPC *should* return incorrect items given.**

end