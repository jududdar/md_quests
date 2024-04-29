# Dason Goldblade
## Dialog

**You say:** `hail`



>**Dason Goldblade says:** Greetings, Soandso.  Are you pure of heart and soul?

**You say:** `Heart and Soul`



>**Dason Goldblade says:** Then choose. Do you wish your purity to be tested by Gregori or Dirkog?

**You say:** `Gregori`



>**Dason Goldblade says:** Gregori is a true and faithful warrior of Tunare.  Read this book and, when you feel confident, hand it back to me.  I will summon Gregori to test you after you have done so.


**You receive:**  [Virtuous Knight](/item/18526)

**You say:** `Dirkog`



>**Dason Goldblade says:** Dirkog is a gruff one, but his faith is what all paladins should strive to equal.  Read this book and return it to me.  After you have done so, I shall summon Dirkog to test you.


**You receive:**  [Walk with Evil](/item/18527)
end

## Turn-Ins



if( **You turn in:** [Virtuous Knight](/item/18526)) then 


>**Dason Goldblade says:** Farewell.


**Spawn NPC:**  [Gregori Lightbringer](/npc/71089) at (**y:** 1331.1, **x:** 563)


**Dason Goldblade despawns.**

elseif( **You turn in:** [Walk with Evil](/item/18527)) then 


>**Dason Goldblade says:** Farewell.


**Spawn NPC:**  [Dirkog Steelhand](/npc/71077) at (**y:** 1331.1, **x:** 563)


**Dason Goldblade despawns.**

**This NPC *should* return incorrect items given.**

end