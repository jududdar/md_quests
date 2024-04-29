# Josin Faithbringer
## Dialog

**You say:** `Hail`



>**Josin Faithbringer says:** Greetings, Soandso.  Are you ready to begin your test of faith?

**You say:** `test of faith`



>**Josin Faithbringer says:** I have faith that you will do well. Choose Alan or Deric

**You say:** `Alan`



>**Josin Faithbringer says:** Take and read this book. When you are done, hand it back to me and I will summon him.


**You receive:**  [Practical Arts](/item/18540)

**You say:** `Deric`



>**Josin Faithbringer says:** Take and read this book. When you are done, hand it back to me and I will summon him.


**You receive:**  [True Healing](/item/18541)
end


## Turn-Ins



if( **You turn in:** [Practical Arts](/item/18540)) then 


>**Josin Faithbringer says:** Farewell.


**Spawn NPC:**  [Alan Harten](/npc/71080) at (**y:** 1361.6, **x:** 660.7)


**Josin Faithbringer despawns.**

elseif( **You turn in:** [True Healing](/item/18541)) then 


>**Josin Faithbringer says:** Farewell.


**Spawn NPC:**  [Deric Lennox](/npc/71083) at (**y:** 1338.0, **x:** 660.7)


**Josin Faithbringer despawns.**

**This NPC *should* return incorrect items given.**

end