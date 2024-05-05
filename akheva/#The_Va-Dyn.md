# The Va-Dyn







## On NPC Spawn

**Set a timer** named *cast* for 1 seconds

**Set a timer** named *depop* for 3 seconds


## Timer(s)

if(e.timer == "cast") then


**Stop timer** named *cast*


**The Va-Dyn casts:** [Storm Tremor](/spell/2816) on themselves.

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The Va-Dyn despawns.**
end
