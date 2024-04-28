# Magus Frinon
## Dialog

**You say:** `Hail`



>**Magus Frinon says:** Greetings, Soandso.  Have you come here to test your abilities as a magician?

**You say:** `test`



>**Magus Frinon says:** I am glad to hear that. Please choose from one of my instructors. Frederic or Roanis.

**You say:** `Frederic`



>**Magus Frinon says:** Frederic it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the magician Frederic to test you.


**You receive:**  [Forms of Magic](/item/18532)

**You say:** `Roanis`



>**Magus Frinon says:** Roanis it shall be.  Take this book and read it.  When you are finished, hand it back to me and I shall summon the magician Roanis to test you.


**You receive:**  [Channeling](/item/18533)
end

## Turn-Ins



if **You turn in:** [Forms of Magic](/item/18532)


>**Magus Frinon says:** Till next time!  Farewell!


**Spawn NPC:**  [Frederic Calermin](/npc/71088) at (**y:** 1304.1, **x:** 614.5)


**Magus Frinon despawns.**

elseif **You turn in:** [Channeling](/item/18533)


>**Magus Frinon says:** Till next time!  Farewell!


**Spawn NPC:**  [Roanis Elindar](/npc/71094) at (**y:** 1304.1, **x:** 614.5)


**Magus Frinon despawns.**

**This NPC *should* return incorrect items given.**

end