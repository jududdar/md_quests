# The Insanity Crawler







## On NPC Spawn

**Set a timer** named *cast* for 1 seconds

**Set a timer** named *depop* for 3 seconds


## Timer(s)

if(e.timer == "cast") then


**Stop timer** named *cast*


**The Insanity Crawler casts:** [Thought Vortex](/spell/2817) on themselves.

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**The Insanity Crawler despawns.**
end
