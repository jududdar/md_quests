# Sarkis Ebonblade
## Dialog

**You say:** `Hail`



>**Sarkis Ebonblade says:** Greetings. Soandso.  Have you come here to test your dark powers of skill and spell casting?

**You say:** `test`



>**Sarkis Ebonblade says:** You will be tested by either Gragrot or Tynicon.  Choose one!

**You say:** `Gragrot`



>**Sarkis Ebonblade says:** Gragrot it is!  Take this book and read it.  When you are finished, hand it back to me and I shall summon Gragrot to test you.


**You receive:**  [Shadowy Virtues](/item/18524)

**You say:** `Tynicon`



>**Sarkis Ebonblade says:** Tynicon it is!  Take this book and read it.  When you are finished, hand it back to me and I shall summon Tynicon to test you.


**You receive:**  [Knights of the Malign](/item/18525)
end


## Turn-Ins



if( **You turn in:** [Shadowy Virtues](/item/18524)) then 


>**Sarkis Ebonblade says:** Farewell.


**Spawn NPC:**  [Gragrot](/npc/71063) at (**y:** 1351.9, **x:** 563.3)


**Sarkis Ebonblade despawns.**

elseif( **You turn in:** [Knights of the Malign](/item/18525)) then 


>**Sarkis Ebonblade says:** Till next time!  Farewell!


**Spawn NPC:**  [Tynicon DLin](/npc/71098) at (**y:** 1351.9, **x:** 563.3)


**Sarkis Ebonblade despawns.**

**This NPC *should* return incorrect items given.**

end