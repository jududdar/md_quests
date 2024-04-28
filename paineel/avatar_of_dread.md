# avatar of dread
count = 0;

## On NPC Spawn

**Set a timer** named *shout* for 17 seconds
## Timer(s)

if(e.timer == "shout") then


count = count + 1;

if(count) then


**avatar of dread shouts:** <span class="text-danger">Grrrraaaaarrrrrg! The stench of fear permeates the walls of this city! I will forge one item for the faithful of our Lord Cazic-Thule! Make haste!  My time here is short!</span>

if(count == 10) then


**avatar of dread despawns.**
end

## Turn-Ins





if **You turn in:** [Mundane Shield](/item/14105)


>**avatar of dread says:** Wear this shield imbued with my very essence. Wear it in honor of your great services to our Lord Cazic-Thule!


* __Faction:__ [Heretics](/faction/265) (50)


* __Faction:__ [Deepwater Knights](/faction/242) (-50)


* __Faction:__ [Gate Callers](/faction/254) (-50)


* __Faction:__ [Craftkeepers](/faction/231) (-50)


* __Faction:__ [Crimson Hands](/faction/233) (-50)


 **You receive:**  [Dread Forged Shield](/item/14107) (+1000 exp)


**avatar of dread despawns.**

**This NPC *should* return incorrect items given.**
