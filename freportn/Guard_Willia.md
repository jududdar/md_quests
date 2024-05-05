# Guard Willia



[Guard Willia](/npc/8110) is a level 6 Guard Warrior that spawns in [North Freeport](/zone/8).



## On NPC Spawn

**Set a timer** named *depop* for 1200 seconds


## Dialog

**You say:** `hail`



>**Guard Willia says:** Please, let me go. I shall leave the [Freeport Militia]. I did not know they were such a vile group.


**Stop timer** named *depop*


**Set a timer** named *cry* for 30 seconds

**You say:** `freeport militia`



>**Guard Willia says:** I thought they were nothing more than the local militia. Little did I know they were so vile. Now I am stuck [here] and I ask for your forgiveness.

**You say:** `why are you here`



>**Guard Willia says:** I came here to escape the militia and ask [Merko to forgive] me.

**You say:** `merko to forgive`



>**Guard Willia says:** I had a small encounter with his wife, my aunt. She was quite red after that altercation. I guess I upset her in a great way, somehow. Could you please go ask Merko to forgive [Willia]. I shall wait here for his answer.
end



## Timer(s)

if(e.timer == "depop") then


**Guard Willia despawns.**

elseif(e.timer == "cry") then


>**Guard Willia says:** Please do not harm me!! I am a lady underneath this garb. I just wanted to join the [Freeport Militia] to help my people.. Please.. Please.. I am nobody. Marr have mercy. I give you the truth. Is that not what you stand for? Merko is my Uncle!!


**Stop timer** named *cry*


**Set a timer** named *run* for 60 seconds

elseif(e.timer == "run") then


>**Guard Willia says:** Thank you, my friend. I shall mend my ways.. maybe.


e.self:SetRunning(true);


eq.start(14);
end
