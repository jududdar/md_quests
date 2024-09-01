# Sigan Ilbirkun

[Sigan Ilbirkun](/npc/70008) is a level 20 Dwarf Warrior that spawns in [Dagnor's Cauldron](/zone/70).

Their primary faction is [Storm Guard](/faction/312).

## Dialog
fac = e.other:GetFaction(e.self);

if(fac < 7) then
**You say:** `hail`

>**Sigan Ilbirkun says:** Hail!! You are welcome to rest here.
**Signaled to:**  [Ghilanbiddle Nylwadil](/npc/70007)
**You say:** `escort`

>**Sigan Ilbirkun says:** Yes. Follow me closely!!
eq.move_to(-143, 1203, 142, 0,false);

else
>**Sigan Ilbirkun says:** Your shifty eyes tell me that you are no ally of the Stormguard.



