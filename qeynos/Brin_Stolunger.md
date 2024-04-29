# Brin Stolunger
## Dialog



**You say:** `Hail`



>**Brin Stolunger says:** What?  What?!!  Are we a [young steel warrior]..  Or another [spectator] for the Arena?

**You say:** `spectator`



>**Brin Stolunger says:** As I thought!!  You shall be better off upon the ramparts of the arena.  It would be dreadful to see a fine citizen injured in the arena.

**You say:** `young steel warrior`



if( **Faction is** >= Amiable) then 



>**Brin Stolunger says:** I say!! Good show!! I see the look of the warrior in you. Some day you may be as great as Brin Stolunger. Ha!! Still, you are surely wet behind the ears. You will need to polish your skills. Take this sack. Return it to me when you have filled it with 5 bat wings and 5 snake scales. Be sure you combine the contents of the bag before you give it back to me. Now, be off!!



**You receive:**  [Empty Arena Sack](/item/17935)


elseif( **Faction is** == Indifferent) then



>**Brin Stolunger says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Brin Stolunger says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!

end

## Turn-Ins





if( **Faction is** >= Amiable) then 


if( **You turn in:** [Full Arena Sack](/item/13399)) then 



>**Brin Stolunger says:** Jolly good!! You are clearly on your way to being a fine addition to the Steel Warriors. Now you must take this message to the person noted. All shall be explained.







* __Faction:__ [Steel Warriors](/faction/311) (10)



* __Faction:__ [Guards of Qeynos](/faction/262) (2)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)



* __Faction:__ [The Freeport Militia](/faction/330) (-1)



* __Faction:__ [Knights of Truth](/faction/281) (2)



 **You receive:**  [A Sealed Letter](/item/18893) (+10000 exp)


elseif( **You turn in:** [Letter of Recommendation](/item/18895)) then 



>**Brin Stolunger says:** So I see you have performed the test of undead. Good show. Now it is time you truly tested your mettle. Take this note to Grahan Rothkar. He can be found beneath the arena in the pens. May you live to join our brotherhood.







* __Faction:__ [Steel Warriors](/faction/311) (10)



* __Faction:__ [Guards of Qeynos](/faction/262) (2)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)



* __Faction:__ [The Freeport Militia](/faction/330) (-1)



* __Faction:__ [Knights of Truth](/faction/281) (2)



 **You receive:**  [A Sealed Letter](/item/18894) (+20000 exp)


**This NPC *should* return incorrect items given.**


