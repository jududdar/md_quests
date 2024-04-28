# Holwin
## Dialog

**You say:** `Hail`



>**Holwin says:** Peace to you, Soandso.  I see that you have come far along the path of tranquility and enlightenment.  Do you wish to test yourself further, and perhaps complete the path you started on so long ago?

**You say:** `test`



>**Holwin says:** Then, choose. Do you wish to be tested by Ton Po or Wu?

**You say:** `wu`



>**Holwin says:** Take this and read it.  Once you are finished, I will summon the Tranquil's most enlightened follower.


**You receive:**  [Strength](/item/18539)

**You say:** `ton po`



>**Holwin says:** Take this book and read about the legendary Ton Po.  When you are finished, hand it back, and I will summon the master for you.


**You receive:**  [Tranquility](/item/18538)
end

## Turn-Ins



if **You turn in:** [Strength](/item/18539)


>**Holwin says:** Farewell.


**Spawn NPC:**  [Wu the Enlightened](/npc/71097) at (**y:** 1332.3, **x:** 660.0)


**Holwin despawns.**

elseif **You turn in:** [Tranquility](/item/18538)


>**Holwin says:** Farewell.


**Spawn NPC:**  [Ton Po](/npc/71096) at (**y:** 1315.0, **x:** 660.0)


**Holwin despawns.**

**This NPC *should* return incorrect items given.**

end