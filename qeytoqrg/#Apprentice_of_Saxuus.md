# Apprentice of Saxuus



[Apprentice of Saxuus](/npc/4170) is a level 30 Wood Elf Druid that spawns in [Qeynos Hills](/zone/4).



## On NPC Spawn

e.self:SetRunning(true);


## Dialog

**You say:** `hail`



>**Apprentice of Saxuus says:** Hello Soandso, nice to meet you.  I just came out to run some [errands].

**You say:** `errands`



>**Apprentice of Saxuus says:** Mostly preparations, meeting with delegates from Mr. Bayle, and from Surefall to make sure all [goes well].

**You say:** `goes well`



>**Apprentice of Saxuus says:** Oh my! You haven't heard?  Well that is a shame, it's big [news].  I would have imagined that more people would have been informed.

**You say:** `news`



>**Apprentice of Saxuus says:** The big news! The powers that be are allowing access to [Jaggedpine] again.  There are dangers involved in opening the portal, but it was essential.

**You say:** `jaggedpine`



>**Apprentice of Saxuus says:** Jaggedpine is the buffer between the Unkempt Forest, and Surefall.  It was closed many years ago by Antonius III to protect the outside world from the oft aggressive residents of the [Unkempt] Forest.

**You say:** `Unkempt`



>**Apprentice of Saxuus says:** The Unkempt are a radical sect of druids and rangers.  They are protective of their lands, so much so that they can be dangerous to all that don't follow their ways.  Honestly I believe they mean well, however they are so extreme in their convictions that I hope they remained locked away.  Even with all that in mind, we are left with very few options, allowing [access] to Jaggedpine is the best of them.

**You say:** `access`



>**Apprentice of Saxuus says:** Well, when Jaggedpine was sealed a few of its original denizens chose to stay there.  There is still a small colony.  Recently, the gnolls of Blackburrow managed to penetrate the seal protecting Jaggedpine.  Lord Antonious has agreed to allow access to Jaggedpine as to better protect those that are living there.
end



## Arrive at Waypoint Script

if(e.wp == 0 or e.wp == 1 or e.wp == 2 or e.wp == 3 or e.wp == 4 or e.wp == 5 or e.wp == 6 or e.wp == 7 or e.wp ==8 or e.wp == 9 or e.wp == 10) then


>**Apprentice of Saxuus says:** Nice day for a walk, wouldn't you say?
end