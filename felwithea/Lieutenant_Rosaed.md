# Lieutenant Rosaed



[Lieutenant Rosaed](/npc/61085) is a level 43 Guard Paladin that spawns in [Northern Felwithe](/zone/61).



## Dialog

**You say:** `hail`



>**Lieutenant Rosaed says:** What are you doing up here?  This area is for the Koada'Vie only!  If you are not a [defender of Felwithe], leave at once!!

**You say:** `what.* defender`




>**Lieutenant Rosaed says:** All paladins who have been charged with the defense of Felwithe are called Defenders.

**You say:** `defender of felwithe`



if **Faction** >= Amiable then




>**Lieutenant Rosaed says:** Hmmph!!  You are a little short to be a guard.  Let us get to work then.  There is much to do.  I have news of a [frightening development] of late.


elseif **Faction** >= Indifferent then



>**Lieutenant Rosaed says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


else



>**Lieutenant Rosaed says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!


**You say:** `frightening development`



if **Faction** >= Amiable then




>**Lieutenant Rosaed says:** Felwithe weeps!! Our beautiful flower, Princess Lenya Thex, has been reported missing! Lord Tynkale says he is looking into the matter, but I fear he is taking far too long.  I have heard that a man named Tolon Nurbyte has been seen in the city lately.  He looks like a shady one.  I would seek him out for answers to her disappearance.


elseif **Faction** >= Indifferent then



>**Lieutenant Rosaed says:** When you have furthered your service to the Paladins of Tunare, we shall make conversation.


else



>**Lieutenant Rosaed says:** You have some nerve to approach a loyal member of the Paladins of Tunare! Run, while you can!

end

