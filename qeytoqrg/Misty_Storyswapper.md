# Misty Storyswapper

[Misty Storyswapper](/npc/4023) is a level 13 Half Elf Bard that spawns in [Qeynos Hills](/zone/4).

Their primary faction is [League of Antonican Bards](/faction/284).

## Dialog
**You say:** `hail`

>**Misty Storyswapper says:** Nice to meet you, Soandso. If you are a fellow bard. I must inform you that you will make no profit around here. Not with Guard McCluskey around.
**You say:** `Guard McCluskey`

>**Misty Storyswapper says:** I will tell you no more. I do not wish to end up boxed and buried. Just stay away from Guard McCluskey. He is no honorable man.





## Arrive at Waypoint Script
if(e.wp == 1 or e.wp == 6) then
e.self:SetRunning(true);
elseif(e.wp == 4 or e.wp == 7) then
e.self:SetRunning(false);

