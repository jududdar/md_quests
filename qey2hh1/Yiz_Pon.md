# Yiz Pon



[Yiz Pon](/npc/12006) is a level 5 Human Wizard that spawns in [Western Plains of Karana](/zone/12).





## Dialog

**You say:** `hail`



>**Yiz Pon says:** Argh... The [beasts] are on my tail. They will find me soon... I gave them the [skull] and still they pursue me!

**You say:** `skull`



>**Yiz Pon says:** The skull of Wun Toque! I have found it. And have learned the location of its eyes! But now the [beasts] have it and I must flee...

**You say:** `beasts`



>**Yiz Pon says:** Here... No time left... Take this please... My brother [Hyrill] is staying in [Freeport]. Please... Ugh... Must keep moving...


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/18010" data-url="18010" class="tooltip-link link">Torn Parchment</a>


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

