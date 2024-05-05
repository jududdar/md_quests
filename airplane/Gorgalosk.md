# Gorgalosk



[Gorgalosk](/npc/71021) is a level 60 Gorgon Warrior that spawns in [Plane of Sky](/zone/71).



## Dialog

**You say:** `hail`



>**Gorgalosk says:** Greetings, Soandso. This is my domain and I hope you have a peaceful stay. That is, unless the [lunatic sent you].

**You say:** `lunatic sent me`



>**Gorgalosk says:** Oh, I see. I suppose you [want these cursed markers] that lunatic made me hold?

**You say:** `cursed markers`



>**Gorgalosk says:** I am afraid that I can not just give them away. The lunatic had them cursed. They make me do [strange things]

**You say:** `strange things`



>**Gorgalosk says:** Like ATTACK you!


**Gorgalosk attacks you.**
end



## On NPC Death

local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();

eq.set_global(sirranName,"3",3,"M20");

**Spawn NPC:**  [Sirran the Lunatic](/npc/71058) at (**y:** 540, **x:** 320)




