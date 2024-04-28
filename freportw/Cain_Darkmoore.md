# Cain Darkmoore
## Dialog

**You say:** `hail`



>**Cain Darkmoore says:** Hail, Soandso! We are the Steel Warriors of Freeport. Our training disciplines have created some of the finest warriors ever to walk upon Norrath. Perhaps the bards shall sing songs of you one day. Let your first mission be the extermination of [Clan Deathfist].

**You say:** `clan deathfist`



>**Cain Darkmoore says:** The orcs of the Commonlands call themselves Clan Deathfist. They have committed many vile acts upon the residents of the Commonlands as well as persons traveling to and from Freeport. They must be destroyed. Go forth to slay them. I shall pay a bounty for every two Deathfist belts. If you are a true warrior of the bunker. perhaps you can begin with [the green and blue].

**You say:** `bigger problem`



>**Cain Darkmoore says:** The bigger problem is the Freeport Militia. Go to the Hall of Truth and speak with the Knights of Truth about that. They have already started their campaign to rid the city of the militia. The so-called Freeport Militia is not to be trusted.

**You say:** `green and blue`



>**Cain Darkmoore says:** The green and blue was a test for all skilled warriors. But we have no more bunker battle blades to spare, and I can not offer you the green and the blue. We must prepare for war!!

**You say:** `bunker battle blade`



>**Cain Darkmoore says:**  The bunker battle blade was crafted and enchanted for use by warriors only. It has the power to strike down those creatures which hide behind their magic. Once bestowed upon a warrior, it cannot leave your side or it shall vanish from this realm forever. One must perform the [green and blue] to earn such a blade.

**You say:** `opal`



>**Cain Darkmoore says:** Opal. Beautiful Opal Darkbriar. Never have I gazed upon a more beautiful creature. She works as a librarian at the Academy of Arcane Science. Some day she shall be mine. A warrior as bold as myself deserves the very best and she is truly that.
end

## Turn-Ins




local count =  **You turn in:**  { [Deathfist Slashed Belt](/item/13916)}, 2

if(count > 0) then


repeat



>**Cain Darkmoore says:** Very fine work Soandso. With your help, we shall soon rid the commonlands of the orcs. Then we can move on to a [bigger problem].



* __Faction:__ [Steel Warriors](/faction/311) (5)



* __Faction:__ [Guards of Qeynos](/faction/262) (1)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)



* __Faction:__ [The Freeport Militia](/faction/330) (-1)



* __Faction:__ [Knights of Truth](/faction/281) (1)



 **You receive:** 0 (+17750 exp)



count = count - 1;


until count == 0;

elseif **You turn in:** [A tattered note](/item/18748)


>**Cain Darkmoore says:** Welcome to the Steel Warriors, young warrior. It is time to prove your mettle. Look to the outskirts of Freeport and join the fray. Show Clan Deathfist what a warrior of the bunker can do.


* __Faction:__ [Steel Warriors](/faction/311) (100)


* __Faction:__ [Guards of Qeynos](/faction/262) (20)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-15)


* __Faction:__ [The Freeport Militia](/faction/330) (-15)


* __Faction:__ [Knights of Truth](/faction/281) (20)


 **You receive:**  [Dirty Training Tunic*](/item/13572) (+20 exp)

**This NPC *should* return incorrect items given.**
;

