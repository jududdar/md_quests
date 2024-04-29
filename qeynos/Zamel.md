# Zamel
## On NPC Spawn

**Set a timer** named *help* for 300 seconds
## Timer(s)

local endicRandom = 0;

if(e.timer == "help") then


endicRandom = math.random(100);


if(endicRandom < 16) then



>**Zamel says:** Clean the [aqueducts] they tell me. Peh, they don't pay me enough to climb into that filth!



end

## Dialog

**You say:** `hail`



>**Zamel says:** Greetings, good Soandso.  My name is Zamel and I have the much coveted duty of pulling sludge up out of the pools and [aqueducts] of Qeynos..

**You say:** `aqueducts`



>**Zamel says:** Aye, the aqueducts are a horrible place. I have heard rumors of horrible [beasts] who live under the city in the water and just the other day, a child playing in the water just up and disappeared!

**You say:** `beasts`



>**Zamel says:** I know nothing of what or where they may be, just rumors, friend.  However, should you foolishly choose to enter the waters to brave the possibilities and return with some evidence of the [child's] fate, I would be most appreciative.

**You say:** `child`



>**Zamel says:** The daughter of one of our own guardsmen is missing. He has offered me a reward for any information about her disappearance. So, if you find out anything, let me know and I will cut you in on the reward.
end

## Turn-Ins



if( **You turn in:** [A Small Tattered Dress](/item/13713)) then


>**Zamel says:** Yes,  I do believe this was the child's dress. Here, take this as your share of the reward. Her father will be heartbroken..





* __Faction:__ [Guards of Qeynos](/faction/262) (2)


* __Faction:__ [Antonius Bayle](/faction/219) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-1)


* __Faction:__ [Merchants of Qeynos](/faction/291) (1)


 **You receive:** eq.ChooseRandom( [Hematite](/item/10018), [Hematite](/item/10018), [Golden Ear Stud](/item/10320)) (+5000 exp)

**This NPC *should* return incorrect items given.**
