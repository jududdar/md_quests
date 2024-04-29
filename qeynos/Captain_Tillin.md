# Captain Tillin
## Dialog

**You say:** `hail`



>**Captain Tillin says:** Hail, Soandso! Spend your time wisely in the city of Qeynos. Do not let your mind wander to thoughts of bravado or crime. My guards can easily put to rest any outbreaks. Good day to you, citizen!

**You say:** `executioner`



>**Captain Tillin says:** The executioner is quite an exceptional person.  [Field Marshall Ralem] happened upon her while on a secret operation in Everfrost Peaks.  They fought side by side against some creature the locals named Iceberg.  The creature escaped.  Ralem was grateful and eventually recruited her when she decided to separate from the guards of Halas.

**You say:** `field marshall ralem`



>**Captain Tillin says:** Field Marshall Ralem Christof is in charge of a brigade of roving rangers, druids and warriors.  He hails from the Jaggedpine.  He is quite an exceptional ranger.  No one is ever really sure where he is.  His brigade is constantly on the move.

**You say:** `antonius`



>**Captain Tillin says:** Antonius Bayle is the governor of this great city.  He may well be the most powerful man in all of Norrath.  You just might bump into him on the streets of Qeynos.  He likes to walk among the citizens from time to time.

**You say:** `kane`



>**Captain Tillin says:** Commander Kane Bayle is the highest ranking officer in the Qeynos Guard.  He reports only to Antonius Bayle, his older brother.  You may find Commander Kane in the guardhouse by the city gates, but do not disturb him.  He is a very busy man.

**You say:** `linariu`



>**Captain Tillin says:** Captain Linarius Graffe is in charge of all the Tower Guards of Qeynos.  Every guard tower from the hills of Qeynos to the plains of Karana is under his control.  He commands his guards from a great bridge keep in northern Karana.



**You say:** `corrupt.* guard`



>**Captain Tillin says:** Corruption among my guards!  Are you mad?  Begone with your wild accusations!
end

## Signals

>**Captain Tillin says:** Ah.  Good.  You have arrived.  [Executioner], could you please visit McNeal Jocub at Fish's Tavern.  He has violated our laws and the sentence is death.

**Signaled to:**  [Executioner](/npc/1202)
## Turn-Ins

local fang = 0;





if( **You turn in:** [Gnoll Fang](/item/13915), [Gnoll Fang](/item/13915), [Gnoll Fang](/item/13915), [Gnoll Fang](/item/13915)) then 


fang = 4;

elseif( **You turn in:** [Gnoll Fang](/item/13915), [Gnoll Fang](/item/13915), [Gnoll Fang](/item/13915)) then



fang = 3;

elseif( **You turn in:** [Gnoll Fang](/item/13915), [Gnoll Fang](/item/13915)) then


fang = 2;

elseif( **You turn in:** [Gnoll Fang](/item/13915)) then


fang = 1;

elseif( **You turn in:** [A tattered note](/item/18815)) then


>**Captain Tillin says:** I heard you were on your way. I have called for the state [executioner]. She should be on her way now. She will deal with our friend, McNeal Jocub. Thank you for your help, citizen.


* __Faction:__ [Guards of Qeynos](/faction/262) (40)


* __Faction:__ [Antonius Bayle](/faction/219) (6)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-6)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-10)


* __Faction:__ [Merchants of Qeynos](/faction/291) (4)


 **You receive:**  [Medal of Merit](/item/13305) (+10 exp)


**Spawn NPC:**  [Executioner](/npc/1202) at (**y:** 75, **x:** -412)

elseif( **You turn in:** [A Tattered Cloth Note](/item/18912)) then


>**Captain Tillin says:** So, an assassin has been sent to Qeynos! I shall have my guards keep an eye out for any suspicious looking visitors. As for you... you should speak with the Surefall Glade ambassador. Ambassador Gash is staying at the Lion's Mane Inn here in South Qeynos. Inform him that [an assassin has been sent to kill] him. Do not let the assassin near him!





* __Faction:__ [Guards of Qeynos](/faction/262) (5)


* __Faction:__ [Antonius Bayle](/faction/219) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)


* __Faction:__ [Merchants of Qeynos](/faction/291) (1)


 **You receive:** 0 (+10 exp)

elseif( **You turn in:** [Compiled Report](/item/8280)) then


>*Captain Tillin scans the report with a furrowed brow. 'So the threat is worse then we had anticipated. The intelligence we have gathere is true. We have little time, return to Sergeant Caelin and give him these orders. Time is of the essence. Hurry now, these people are in grave danger and something must be done to stop this!*


 **You receive:**  [Orders for Sergeant Caelin](/item/8287) 



if(fang > 0) then


repeat



>**Captain Tillin says:** Very good! One less gnoll the people of Qeynos need to fear. Here is your bounty as promised.







* __Faction:__ [Guards of Qeynos](/faction/262) (3)



* __Faction:__ [Antonius Bayle](/faction/219) (1)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)



* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)



* __Faction:__ [Merchants of Qeynos](/faction/291) (1)



 **You receive:**  [Moonstone](/item/10070) (+8500 exp)



fang = fang - 1;


until fang == 0





**This NPC *should* return incorrect items given.**


