# avatar of terror
count = 0;

## On NPC Spawn

**Set a timer** named *shout* for 17 seconds
## Timer(s)

if(e.timer == "shout") then


count = count + 1;

if(count) then


**avatar of terror shouts:** <span class="text-danger">Grrrraaaaarrrrrg! The stench of fear permeates the walls of this city! I will forge one item for the faithful of our Lord Cazic-Thule! Make haste!  My time here is short!</span>

if(count == 10) then


**avatar of terror despawns.**
end

## Turn-Ins





if( **You turn in:** [Mundane Mask](/item/14106)) then 


>**avatar of terror says:** I grant you a mask crafted with my own essence! Wear it in honor of your devotion to our Lord Cazic-Thule!


* __Faction:__ [Heretics](/faction/265) (50)


* __Faction:__ [Deepwater Knights](/faction/242) (-50)


* __Faction:__ [Gate Callers](/faction/254) (-50)


* __Faction:__ [Craftkeepers](/faction/231) (-50)


* __Faction:__ [Crimson Hands](/faction/233) (-50)


 **You receive:**  [Terror Forged Mask](/item/14108) (+5000 exp)


**avatar of terror despawns.**

**This NPC *should* return incorrect items given.**
