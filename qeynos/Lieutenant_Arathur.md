# Lieutenant Arathur


## Arrive at Waypoint Script
  if(e.wp == 12) then

>**Lieutenant Arathur says:** Guard, stand up straight!

**Signaled to:**  [Guard Jerith](/npc/1002)

**Signaled to:**  [Guard Dunix](/npc/1181)
  elseif(e.wp == 28) then

>**Lieutenant Arathur says:** Guard, stand up straight!

**Signaled to:**  [Guard Beren](/npc/1090)

**Signaled to:**  [Guard Corshin](/npc/1091)
  elseif(e.wp == 38) then

>**Lieutenant Arathur says:** Guard, stand up straight!

**Signaled to:**  [Guard Mezzt](/npc/1001)

**Signaled to:**  [Guard Phaeton](/npc/1189)

**Signaled to:**  [Guard Cyrillian](/npc/1006)

**Signaled to:**  [Guard Forbly](/npc/1174)
 end  



## Dialog

**You say:** `hail`



>**Lieutenant Arathur says:** Hail, Soandso!  Lieutenant Arathur Swelnik at your service.  I take great pride in keeping Qeynos safe and proper.  I also try to bring the word of [Mithaniel Marr] to the people of this fine city.

**You say:** `marr`



>**Lieutenant Arathur says:** Mithaniel Marr is the Lord of Valor and my personal source of power and inspiration.  You see, I was orphaned as a small child and raised by the Priests of Marr in [Freeport].  I have dedicated my life to protecting the innocent.  I now use the glorious powers that my faith in the Truthbringer has provided to help bring honor to the city of Qeynos.

**You say:** `freeport`



if **Faction** >= Indifferent then



>**Lieutenant Arathur says:** Freeport is the city of my birth.  It is not what it once was, though.  Thugs and bandits patrol its streets.  My comrades in the Knights of Truth have managed to protect the northern parts of the city but I fear they are outnumbered and will soon have to flee Freeport altogether.  If it were not for my sworn duty here, I would join their noble [crusade].




else



>**Lieutenant Arathur says:** Hurmp!  You have not proven yourself loyal to Qeynos.  Begone!




**You say:** `crusade`



if **Faction** >= Amiable then



>**Lieutenant Arathur says:** The Knights of Truth fight a never-ending battle against the corrupt and vicious Freeport Milita.  If you are going to Freeport, you might want to meet up with Knight Rolius and let him know you are a friend of Arathur.  They can always use another able body.



elseif **Faction** >= Indifferent then



>**Lieutenant Arathur says:** While you are a fine and loyal citizen, I simply cannot trust you with that information as yet.


else



>**Lieutenant Arathur says:** Hurmp!  You have not proven yourself loyal to Qeynos.  Begone!







**You say:** `kane`



>**Lieutenant Arathur says:** Commander Kane Bayle is the commander of all the Qeynos Guard.  He is second only to his brother, Antonius Bayle.  His post is in the guard house at the city gates.  Mind you, do not bother him, he has a bit of a temper.



**You say:** `circle.* unseen hand`



>**Lieutenant Arathur says:** The Circle of the Unseen Hand?  I have heard nothing of them.  Are they some sort of performing magic troupe?
end