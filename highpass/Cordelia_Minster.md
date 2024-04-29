# Cordelia Minster
## Dialog



**You say:** `hail`



>**Cordelia Minster says:** Greetings!  I am Cordelia, a traveling piper. I am afraid I cannot play a tune for you, however, as my [flute] is gone.




**You say:** `flute`



>**Cordelia Minster says:** I traded my flute to a hermit in the southern plains of Karana. I had a spare flute, but that was taken from me by some bandits. If you could find this hermit and ask him for my flute back, I would be most appreciative.
end

## Turn-Ins




if( **You turn in:** [A Cracked Flute](/item/13310)) then 


>**Cordelia Minster says:** Why thank you, kind adventurer! Here is a little something to keep food in your belly. Now back to practice. La la la..


* __Faction:__ [League of Antonican Bards](/faction/284) (5)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Mayong Mistmoore](/faction/285) (-1)


 **You receive:**  [Winds of Karana sheet 2](/item/13119) (+1000 exp)

**This NPC *should* return incorrect items given.**

## On NPC Spawn

**Set a timer** named *timecheck* for 60 seconds
## Timer(s)

if ( e.timer == "timecheck" and not e.self:IsEngaged() ) then




local zoneTime = eq.get_zone_time()["zone_hour"];



if ( zoneTime < 19 and zoneTime > 6 ) then



**Cordelia Minster despawns.**

end

## On NPC Death

**Spawn NPC from spawn group:** [Cytodl Krish](/npc/336269) after 1200 second(s)