# General Keraj



[General Keraj](/npc/155162) is a level 50 Guard Warrior that spawns in [The City of Shar Vahl](/zone/155).



## On NPC Spawn

**Set a timer** named *1* for 210 seconds

**Set a timer** named *2* for 220 seconds

**Set a timer** named *3* for 230 seconds

**Set a timer** named *4* for 400 seconds

**Set a timer** named *5* for 410 seconds

**Set a timer** named *6* for 420 seconds

**Set a timer** named *7* for 430 seconds

**Set a timer** named *8* for 440 seconds

**Set a timer** named *9* for 450 seconds

**Set a timer** named *10* for 700 seconds

**Set a timer** named *11* for 705 seconds


## Timer(s)

if(e.timer=="1") then


>**General Keraj says:** Nay friend, we appear to be making decent progress. The grimling numbers are increasing, but so are ours. Many of the newcomers are working with us in the moor and forests. The influx of adventurers has provided us with some amazing new leaders. They are so full of energy and fearless ambition


**Stop timer** named *1*

if(e.timer=="2") then


>**General Keraj says:** Aye friend, I guess that you are right. I am just ready to head back into the forest. I want to take those mines back before this season ends. We built this city from the acrylia in those mines and now look at us. We have to resort to using any scrap of acrylia that we can find.


**Stop timer** named *2*

if(e.timer=="3") then


>**General Keraj says:** Aye mate, a few games would be a fine sight. Well, let me get back in there. I'm sure that'll want to keep talking. Bah...


eq.stop_timer("3")

if(e.timer=="4") then


**Signaled to:**  [High Spiritist Jimuul](/npc/155161)


**Stop timer** named *4*

if(e.timer=="5") then


>**General Keraj says:** Tell him what you have told him every season prior to this... We are keeping them from over running the city, the moor is clear with the exception of a few camps, and the forest outpost still stands. What more is there to report?


**Stop timer** named *5*

if(e.timer=="6") then


**Signaled to:**  [High Spiritist Jimuul](/npc/155161)


**Stop timer** named *6*

if(e.timer=="7") then


**Signaled to:**  [Pathmaster Kharin](/npc/155160)


**Stop timer** named *7*

if(e.timer=="8") then


**Signaled to:**  [High Spiritist Jimuul](/npc/155161)


**Stop timer** named *8*

if(e.timer=="9") then


>**General Keraj says:** Then make no demands of my soldiers beyond what they are already doing. It will serve no one to have our resources depleted before you can even produce the question I am supposed to answer. If you need more headway in the area of the mines, then tell the king that we need new incentives to compel the outsiders to aid us in that area. We cannot take that area with my men alone and I am not sending soldiers in to die without a known goal!


**Stop timer** named *9*

if(e.timer=="10") then


>**General Keraj says:** Bah, I do not know why I let these meetings bother me. They have little relevance to our current battle. The mines have been lost to those creatures and their ranks seem to swell to greater numbers with each day that passes.


**Stop timer** named *10*

if(e.timer=="11") then


**Set a timer** named *1* for 210 seconds


**Set a timer** named *2* for 220 seconds


**Set a timer** named *3* for 230 seconds


**Set a timer** named *4* for 400 seconds


**Set a timer** named *5* for 410 seconds


**Set a timer** named *6* for 420 seconds


**Set a timer** named *7* for 430 seconds


**Set a timer** named *8* for 440 seconds


**Set a timer** named *9* for 450 seconds


**Set a timer** named *10* for 700 seconds
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





