# Clarisa Spiritsong
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Clarisa Spiritsong says:** Hi there Soandso! I give three sections of the test of songs, Denise does the rest. Do you wish to take the test of pitch, voice, or tone?

**You say:** `pitch`




>**Clarisa Spiritsong says:** The pitch that we sing and play has a great effect on those who listen.  Keep this in mind, Soandso, and you shall always be welcome in taverns and inns.  Now, I need you to return to me a phosphoric globe, a shimmering diamond, and a crude wooden flute.

**You say:** `voice`




>**Clarisa Spiritsong says:** The sweet sounds rising forth from our throats are what make us truly great.  Go forth and give voice to your songs, and return to me a platinum disc, a music box, and a light woolen mantle.  If you do this, I shall give you the mantle of the songweaver.  Good luck!

**You say:** `tone`




>**Clarisa Spiritsong says:** Tone is important to all singers.  Prove to me that you can keep your tone even and pure by bringing me an ochre tessera, a songbird statuette, and a light woolen mask.  If you do this, I will give you the mask of song.
end

## Turn-Ins



if( **You turn in:** [Phosphoric Globe](/item/20947), [Shimmering Diamond](/item/20824), [Crude Wooden Flute](/item/20825)) then 



>**Clarisa Spiritsong says:** The songsmith Ervaj crafted this flute. It is now yours, Soandso.


 **You receive:**  [Ervaj's Flute of Flight](/item/27722) (+100000 exp)

elseif( **You turn in:** [Platinum Disc](/item/20940), [Music Box](/item/20822), [Light Woolen Mantle](/item/20823)) then 


>**Clarisa Spiritsong says:** You are truly a master of songs, Soandso.


 **You receive:**  [Mantle of the Songweaver](/item/27721) (+100000 exp)

elseif( **You turn in:** [Ochre Tessera](/item/20933), [Light Woolen Mask](/item/20821), [Songbird Statuette](/item/20820)) then 


>**Clarisa Spiritsong says:** Take this mask. You have earned it.


 **You receive:**  [Mask of Song](/item/27720) (+100000 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Clarisa Spiritsong despawns.**




