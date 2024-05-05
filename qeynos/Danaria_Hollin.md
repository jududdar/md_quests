# Danaria Hollin



[Danaria Hollin](/npc/1066) is a level 20 Erudite Enchanter that spawns in [South Qeynos](/zone/1).



## Arrive at Waypoint Script

if(e.wp == 5) then


>**Danaria Hollin says:** I would like an Erudian tart, please.


**Signaled to:**  [Karn Tassen](/npc/1110)

elseif(e.wp == 8) then


>**Danaria Hollin says:** Time in the pub shall keep them from advancing to the next level of the mind. When will they learn?

elseif(e.wp == 26) then


>**Danaria Hollin says:** A magnificent piece of workmanship! The clock, too.
end



## Signals

>**Danaria Hollin says:** Just get me the tart and put your eyes back in your sockets or I'll pry them out for good!


## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then 



>**Danaria Hollin says:** Greetings! Nice to meet someone with manners. I do not see how you people stand to live in this madhouse of ruffians. I would have left weeks ago if I were not waiting for a delivery. Oh, well. Nice to have met you.


else



**Danaria Hollin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!




**You say:** `delivery`



if **Faction** >= Indifferent then



>**Danaria Hollin says:** I am in Qeynos to meet up with a fellow Erudite coming from Freeport. He is two weeks late and I fear the worst. I shall need to hire some lackey to go to Freeport to find him.


else



**Danaria Hollin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!




**You say:** `find`



if **Faction** >= Indifferent then



>**Danaria Hollin says:** Yes, that might work. Please go to Freeport and find him. His name is Palatos Kynarn. Tell him that Danaria has sent you for the painting. And be quick about it! Thank you.


else



**Danaria Hollin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!




**You say:** `donate`



>**Danaria Hollin says:** Why would I donate to such an inferior group of brutes? Go away! You will find no pity here.

end



## Turn-Ins



**This NPC *should* return incorrect items given.**

end