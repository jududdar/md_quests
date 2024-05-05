# An Undead Bard



[An Undead Bard](/npc/89168) is a level 57 Skeleton Shopkeeper that spawns in [Ruins of Sebilis](/zone/89).

local spawn;


## On NPC Spawn

spawn = 0;


## Dialog

**You say:** `hail`



>**An Undead Bard says:** Hail, Soandso. Are you perchance a minstrel?

**You say:** `i am a minstrel`



>**An Undead Bard says:** I, too, am a bard, or was rather. I have been cursed by that blasted pile of bones who calls itself, Trakanon.

**You say:** `trakanon`



>**An Undead Bard says:** He is the undead dragon who rules this realm. I came on a quest seeking strings for my new instrument.

**You say:** `instrument`



>**An Undead Bard says:** I sought to create a Magical Lute.

**You say:** `magical lute`



>**An Undead Bard says:** One that would make me the greatest bard in all the lands! Are you on a similar quest?

**You say:** `similar quest`



>**An Undead Bard says:** Excellent. I have stayed here far too long and I wish to go to my eternal slumber. But before I do so, I ask for one last request.

**You say:** `last request`



>**An Undead Bard says:** Well then, I would ask you a favor for one in return. If I bring that cursed dragon here, will you kill it for me?

**You say:** `kill it for you`



>**An Undead Bard says:** Give me the Mystical Lute Body you have. I will return it, don't worry. I only wish to hold an instrument one last time before I leave.
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_686.png" alt="" /> <a
                                href="/item/20536" data-url="20536" class="tooltip-link link">Mystical Lute Body</a>) then 


>**An Undead Bard says:** I feel so powerful once again...a strange feeling is overcoming me!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_686.png" alt="" /> <a
                                href="/item/20536" data-url="20536" class="tooltip-link link">Mystical Lute Body</a> 

 


**An Undead Bard attacks you.**


spawn = 1;

**This NPC *should* return incorrect items given.**



## On NPC Death

if(spawn == 1) then


**Spawn NPC:**  [\#Trakanon](/npc/89039) at (**y:** -2103, **x:** -693)


spawn = 0;
end





