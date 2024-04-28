# Tunarean Earthmelder
## On NPC Spawn

**Set a timer** named *hum* for 90 seconds
## Timer(s)

>*Tunarean Earthmelder seems to pulse as its roots dig into the ground around it.*
## Dialog

if(**Your level** >= 55) then


**You say:** `hail`




>**Tunarean Earthmelder says:** Hail, my friend. Unfortunately I cannot talk right now. The giants must be dealt with.


**You say:** `giants`




>**Tunarean Earthmelder says:** The giants are continuing to put forth efforts to encroach the lands blessed by Tunare. We need an outrider or preserver to aid us in our continued fight.


**You say:** `preserver`




>**Tunarean Earthmelder says:** Noble preserver, you will be needed to combat the priests of the warbringer. Scouts have reported three priests wandering the Wakening Lands in search of a site to build a shrine to their god. Seek them out, kill them, and bring their heads and those of anyone else involved.


**You say:** `outrider`




>**Tunarean Earthmelder says:** We have need of you to disrupt the construction efforts of the giants in the Wakening Land. Find the frost giant overseer, kill him and any others that are responsible for the building and bring back their heads.

end

## Turn-Ins




if **You turn in:** [Grenk's Head](/item/31424), [Delar's Head](/item/31425), [Bjek's Head](/item/31426), [Derakor's Head](/item/31423)


>**Tunarean Earthmelder says:** You have done well, Soandso.  Here, take this item and use it well! Your efforts will not be forgotten.


 **You receive:**  [Gloves of Earthcrafting](/item/1208) (+1000 exp)

elseif **You turn in:** [Frostgiant Overseers Head](/item/31419), [Kallis' Head](/item/31420), [A bloody protector of Zek's Head](/item/31421), [A smashed protector of Zek's Head](/item/31422)


>**Tunarean Earthmelder says:** You have done well, Soandso.  Here, take this item and use it well! Your efforts will not be forgotten.


 **You receive:**  [Helm of the Tracker](/item/1207) (+1000 exp)

**This NPC *should* return incorrect items given.**
