# Drakis Bloodcaster

## Dialog

**You say:** `hail`



>**Drakis Bloodcaster says:** Greetings, " .. e.other:Race() .. ". Are you ready to begin?

**You say:** `ready`



>**Drakis Bloodcaster says:** Then choose, necromancer. Do you wish to be tested by Dugaas or Jzil?

**You say:** `jzil`



>**Drakis Bloodcaster says:** Take this tome and read it.  When you are finished, return it to me and I will summon Jzil.


**You receive:**  [Shadowy Thoughts](/item/18536)

**You say:** `Dugaas`



>**Drakis Bloodcaster says:** Take this book and read it then.  When you are finished, hand it back to me and I will summon the vile Dugaas.


**You receive:**  [Pomp and Circumstance](/item/18537)
end

## Turn-Ins



if( **You turn in:** [Shadowy Thoughts](/item/18536)) then 


>**Drakis Bloodcaster says:** Farewell.


**Spawn NPC:**  [Jzil GSix](/npc/71074) at (**y:** 1305, **x:** 654.9)


**Drakis Bloodcaster despawns.**

elseif( **You turn in:** [Pomp and Circumstance](/item/18537)) then 


>**Drakis Bloodcaster says:** Farewell.


**Spawn NPC:**  [Dugaas Helpyre](/npc/71084) at (**y:** 1305, **x:** 661.6)


**Drakis Bloodcaster despawns.**

**This NPC *should* return incorrect items given.**

end