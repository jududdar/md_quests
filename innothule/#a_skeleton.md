# a skeleton
## Dialog

**You say:** `hail`



>**a skeleton says:** Avast, matey! Captain Bones here. This here island is mine! Raise anchor and ship out!

**You say:** `captain`



if **Faction** >= Amiable +100 then 




>**a skeleton says:** I wish I could be leaving this isle of the damned, alas, me boat has gone to Prexus' locker. I'll not be leavin' here until I get meself another ship.


elseif **Faction** >= Indifferent then



>**a skeleton says:** You're going to have to prove yourself a stronger aid to my masters, the Darkones.


else



>**a skeleton says:** I would like to assist you, but my masters say you are no friend of the Darkones and would rather see you dead.


end

## Turn-Ins





if **Faction** >= Amiable +100 and  **You turn in:** [Ship in a Bottle](/item/12218)


>**a skeleton says:** Aye, matey! Ye found me another vessel with which to sail the seven seas? Let's be shoving off then! Come on, hop aboard, swabby! Be sure to pick up the minstrel. His hide was last seen by Basher Avisk. Only he be knowin' [where the minstrel ] be.


 **You receive:**  [The Captain](/item/12215) (+25 exp)


**a skeleton despawns.**

**This NPC *should* return incorrect items given.**

