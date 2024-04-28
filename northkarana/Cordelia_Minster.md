# Cordelia Minster



## Arrive at Waypoint Script

if(e.wp == 1 or e.wp == 3 or e.wp == 8) then


e.self:SetRunning(true);

elseif(e.wp == 2 or e.wp == 6 or e.wp == 10) then


e.self:SetRunning(false);
end

## Dialog

**You say:** `hail`



>**Cordelia Minster says:** Greetings!  I am Cordelia, a traveling piper. I am afraid I cannot play a tune for you, however, as my [flute] is gone.

**You say:** `flute`



>**Cordelia Minster says:** I traded my flute to a hermit in the southern plains of Karana. I had a spare flute, but that was taken from me by some bandits. If you could find this hermit and ask him for my flute back, I would be most appreciative.
end

## Turn-Ins




if **You turn in:** [A Cracked Flute](/item/13310)


>**Cordelia Minster says:** Why thank you, kind adventurer! Here is a little something to keep food in your belly. Now back to practice. La la la..


* __Faction:__ [League of Antonican Bards](/faction/284) (5)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**


