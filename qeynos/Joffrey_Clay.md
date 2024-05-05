# Joffrey Clay



[Joffrey Clay](/npc/1123) is a level 61 Human GM Bard that spawns in [South Qeynos](/zone/1).



## Dialog

**You say:** `hail`



>**Joffrey Clay says:** Greetings, friend. My name is Joffrey. I'm trying to learn to play the [flute]. I'm also working on a new song I learned while I was visiting [Kelethin].

**You say:** `kelethin`



>**Joffrey Clay says:** I just got back from a trip to Faydwer. I was over there studying the lore of Tunare, in the beautiful elven city of Kelethin. I highly recommend visiting there as soon as you get a chance.

**You say:** `flute`



>**Joffrey Clay says:** You like my flute? Jusean made it for me. His father was a master instrument craftsman, and Jusean learned his technique very well.

**You say:** `Jusean`



>**Joffrey Clay says:** He should be around here somewhere.  He's kinda lazy, so I imagine he wouldn't stray too far.
end



## Arrive at Waypoint Script

if(e.wp == 1) then


>**Joffrey Clay says:** Belious, I'm working on this new tune I learned on my last trip to Kelethin. It's about Tunare. If you have a free ear, would you care to take a listen?


**Signaled to:**  [Belious Naliedin](/npc/1125)

elseif(e.wp == 2) then


>**Joffrey Clay says:** Ahem. Tunare and the Pact, sung by Joffrey Clay.


e.self:DoAnim(58);


>**Joffrey Clay says:** La da di, la di da.. la da di. la di da..
end



## Turn-Ins



**This NPC *should* return incorrect items given.**

