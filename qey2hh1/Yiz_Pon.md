# Yiz Pon


## Dialog

**You say:** `hail`



>**Yiz Pon says:** Argh... The [beasts] are on my tail. They will find me soon... I gave them the [skull] and still they pursue me!

**You say:** `skull`



>**Yiz Pon says:** The skull of Wun Toque! I have found it. And have learned the location of its eyes! But now the [beasts] have it and I must flee...

**You say:** `beasts`



>**Yiz Pon says:** Here... No time left... Take this please... My brother [Hyrill] is staying in [Freeport]. Please... Ugh... Must keep moving...


**You receive:**  [Torn Parchment](/item/18010)


**Spawn NPC:**  [a Splitpaw assassin](/npc/12005) at (**y:** 1118, **x:** -15467)


**Set a timer** named *assassin* for 60 seconds

**You say:** `hyrill`



>**Yiz Pon says:** There is no time... must keep moving... ugh.
end

## Timer(s)

if(e.timer == "assassin") then


**Stop timer** named *assassin*


>**Yiz Pon says:** Leave me be! I have friends all over the Commonlands who will avenge me!


**Yiz Pon despawns.**
end

## Combat

if(e.joined and **spawned NPC:**  [a Splitpaw assassin](/npc/12005)) then


eq.get_entity_list():GetMobByNpcTypeID( [a Splitpaw assassin](/npc/12005)):Say("You cannot escape the claws of Splitpaw!");


>**Yiz Pon says:** He has found me! Help meeeeeee!
end

