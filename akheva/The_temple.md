# The temple


## On NPC Spawn

**Set a timer** named *cast* for 1 seconds

**Set a timer** named *depop* for 3 seconds


## Timer(s)

if(e.timer == "cast") then


**Stop timer** named *cast*


**The temple casts:** [Shower of Blood](/spell/2815) on themselves.

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The temple despawns.**
end
