# McNeal Jocub
## Dialog

**You say:** `hail`



>**McNeal Jocub says:** Good ta see ya! Now start showin' these poodlewalkers how a real fish drinks!

**You say:** `low`



>**McNeal Jocub says:** This is going to sound crazy, but my main supplier of [Blackburrow Stout] is one of the brewers themselves. I have run too low on the fine brew and need someone to [pick up my shipment].

**You say:** `pick up.* shipment`



>**McNeal Jocub says:** Take this note to the Qeynos Hills. Somewhere there, you shall find a gnoll at night called Gnasher. Give him the note. Now, get moving!


**You receive:**  [A tattered note](/item/18800)

**You say:** `blackburrow stout`



>**McNeal Jocub says:** Keep it down!! So you've heard of Blackburrow Stout? We sell it here in Fish's Backroom. If the Qeynos Guards knew, well.. it wouldn't be such a good thing. The stout is illegal, It's made by the gnolls. It is one of the finest brews you will ever taste. If you want any.. slide me a [moonstone].

**You say:** `moonstone`



>**McNeal Jocub says:** Looking for moonstones, are we? The only way I know of getting a moonstone is to hunt gnolls for Captain Tillin of the Qeynos Guards.
end

## Arrive at Waypoint Script

if(e.wp == 5) then


>**McNeal Jocub says:** Blast!! We are running [low]!!
end

## Signals

>**McNeal Jocub says:** You shall never take me alive!!

**McNeal Jocub attacks NPC:**  [Executioner](/npc/1202)
## Turn-Ins

local moonstone = 0;



if **You turn in:** [Case of Blackburrow Stout](/item/13131)


>**McNeal Jocub says:** Good work, pal. Here's a little dough to spend, just don't spend it at any other bar.


* __Faction:__ [Karana Residents](/faction/345) (30)


* __Faction:__ [Guards of Qeynos](/faction/262) (7)


* __Faction:__ [Priests of Life](/faction/341) (4)


* __Faction:__ [Knights of Thunder](/faction/280) (9)


 **You receive:** None 

elseif **You turn in:** [Moonstone](/item/10070), [Moonstone](/item/10070), [Moonstone](/item/10070), [Moonstone](/item/10070)


moonstone = 4;

elseif **You turn in:** [Moonstone](/item/10070), [Moonstone](/item/10070), [Moonstone](/item/10070)


moonstone = 3;

elseif **You turn in:** [Moonstone](/item/10070), [Moonstone](/item/10070)


moonstone = 2;

elseif **You turn in:** [Moonstone](/item/10070)


moonstone = 1;

if(moonstone > 0) then


repeat



>**McNeal Jocub says:** Here you go then. Don't go tellin' no Guards where that came from, I would hate to rid myself of a good paying customer.



* __Faction:__ [Karana Residents](/faction/345) (1)



* __Faction:__ [Guards of Qeynos](/faction/262) (1)



* __Faction:__ [Priests of Life](/faction/341) (1)



* __Faction:__ [Knights of Thunder](/faction/280) (1)



 **You receive:**  [Black Burrow Stout](/item/13107) (+200 exp)



moonstone = moonstone - 1;


until moonstone == 0

**This NPC *should* return incorrect items given.**
