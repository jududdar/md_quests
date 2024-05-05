# Askr the Lost



[Askr the Lost](/npc/209157) is a level 60 Half Elf Warrior that spawns in [Bastion of Thunder](/zone/209).



## Dialog

**You say:** `hail`



>**Askr the Lost says:** Well done Soandso.  You have succeed where I have failed, but now comes the most dangerous peril the Bastion holds.  The final level of Torden holds the restless spirit of the Rainkeeper himself.  You must find a way to free him from his tormented sleep.  His dreams and visions have coalesced into a dark shade of himself which controls the full fury of the [Storm].




**You say:** `what storm`



>**Askr the Lost says:** The spirit of chaos itself guards the chamber where Karana sleeps.  Chaos will most certain protect the embodiment of his tortured conscious as if it were the Rainkeeper himself.  I am afraid that there is no assistance that I can offer in the task laid out before you aside from opening the vortex to Chaos and offer you Karana's blessing.


**Spawn NPC:**  [A Chaotic Vortex](/npc/209158) at (**y:** -1735, **x:** -1110)
end



## On NPC Spawn

**Set a timer** named *depop* for 3300 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**Askr the Lost despawns.**
end
