# Ratop

[Ratop](/npc/110052) is a level 31 Gnome Rogue that spawns in [Iceclad Ocean](/zone/110).

Their primary faction is [Pirates of Iceclad](/faction/447).

## Dialog

**You say:** `hail`


>**Ratop says:** Squawk! Pieces of eight! Pieces of eight!

if(**spawned NPC:**  [Ritap](/npc/110053)) then

eq.get_entity_list():GetMobByNpcTypeID(110053):Say("The cap'n said PIRATES! Not parrots ye knucklehead!' He whacks the other raider upside the head. 'now whars the tinkered rope!?'");

>**Ratop says:** We be out.  Youll be needin to make more. Arg!





