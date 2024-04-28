# Enchanter Jolas
## Dialog

**You say:** `hail`



>**Enchanter Jolas says:** Greetings, Soandso.  Have you come here to test your powers of enchantment?

**You say:** `test`



>**Enchanter Jolas says:** I am most honored to be able to help you. Please choose from one of my instructors. Lelulean or Enderbite.

**You say:** `enderbite`



>**Enchanter Jolas says:** Enderbite it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon Enchantress Enderbite to test you.


**You receive:**  [Practical Uses](/item/18535)

**You say:** `lelulean`



>**Enchanter Jolas says:** Lelulean it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon Enchantress Lelulean to test you.


**You receive:**  [Tempt and Suggestion](/item/18534)
end

## Turn-Ins



if **You turn in:** [Practical Uses](/item/18535)


>**Enchanter Jolas says:** Till next time!  Farewell!


**Spawn NPC:**  [Enderbite](/npc/71085) at (**y:** 1303.2, **x:** 640)


**Enchanter Jolas despawns.**

elseif **You turn in:** [Tempt and Suggestion](/item/18534)


>**Enchanter Jolas says:** Till next time!  Farewell!


**Spawn NPC:**  [Lelulean](/npc/71104) at (**y:** 1303.2, **x:** 640)


**Enchanter Jolas despawns.**

**This NPC *should* return incorrect items given.**

end