# Alan Harten
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Alan Harten says:** Greetings faithful. Your faith shall be tested this day.  Shall you take the test of courage, skill, or protection?

**You say:** `courage`




>**Alan Harten says:** You have come seeking the knowledge and treasures I possess.  I will impart such things to you, if you do a service to your god.  It matters not who that god may be, but the service and the faith you must exemplify.  Bring to me an ochre tessera, a sky emerald, and a silver hoop.

**You say:** `skill`



>**Alan Harten says:** The test of skill it will be.  Bring to me a golden disc, a piece of dark wood, and a small shield.  You shall be rewarded upon your return.

**You say:** `protection`



>**Alan Harten says:** So, you must be a great protector to have ventured this far.  Bring to me an adumbrate globe, a faintly glowing diamond, and some shiny pauldrons to get your reward.
end

## Turn-Ins



if **You turn in:** [Ochre Tessera](/item/20933), [Silver Hoop](/item/20807), [Sky Emerald](/item/20806)



>**Alan Harten says:** Wonderful! Take this as your reward!


 **You receive:**  [Truewind Earring](/item/14563) (+100000 exp)


**Alan Harten despawns.**

elseif **You turn in:** [Dark Wood](/item/20808), [Gold Disc](/item/20939), [Small Shield](/item/20809)


>**Alan Harten says:** Wonderful! Take this as your reward!


 **You receive:**  [Aegis of the Wind](/item/27716) (+100000 exp)


**Alan Harten despawns.**

elseif **You turn in:** [Adumbrate Globe](/item/20946), [Faintly Glowing Diamond](/item/20810), [Shiny Pauldrons](/item/20811)



>**Alan Harten says:** Wonderful! Take this as your reward!


 **You receive:**  [Pauldrons of Piety](/item/27717) (+100000 exp)


**Alan Harten despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Alan Harten despawns.**



