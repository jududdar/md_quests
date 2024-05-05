# Guard Slacey



[Guard Slacey](/npc/121027) is a level 35 Coldain Warrior that spawns in [Crystal Caverns](/zone/121).



## Dialog

**You say:** `hail`



>**Guard Slacey says:** Shhh... listen. Can you hear them?  They are very close.

**You say:** `close`



>**Guard Slacey says:** What?!? You mean you...


if(**spawned NPC:**  [Guard Evercold](/npc/121026)) then



eq.get_entity_list():GetMobByNpcTypeID( [Guard Evercold](/npc/121026)):Say("Now don't get all in an up roar Slacey. These visitors have no clue what it is like down here. Unless of course, they have talked to the Captain!");



>**Guard Slacey says:** You are right, Evercold. You should go see the Captain to fully understand what is going on here.

end



## Signals

>*Guard Slacey blushes. Be nice Evercold.*


## Turn-Ins



**This NPC *should* return incorrect items given.**

end