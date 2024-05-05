# The study







## On NPC Spawn

if(**spawned NPC:**  [a coterie servant](/npc/160097)) then


**Set a timer** named *depop_servant* for 10 seconds
end



## Combat

>*The study locks behind you.. You get the feeling you are not alone.*

**Set a timer** named *servant* for 5 seconds


## Timer(s)

if(e.timer == "servant") then


**Stop timer** named *servant*


**Stop timer** named *depop_servant*


**Spawn NPC:**  [a coterie servant](/npc/160097) at (**y:** 288, **x:** -719)


**The study despawns.**

elseif(e.timer == "depop_servant") then


**Stop timer** named *depop_servant*


**Despawn NPC:**  [a coterie servant](/npc/160097)
end
