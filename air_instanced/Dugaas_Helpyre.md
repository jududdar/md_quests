# Dugaas Helpyre
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Dugaas Helpyre says:** So, you dare be seen in my precense. Truly a brave fool you are. You come seeking fame and glory here do you? Well fool, perhaps you will get what you seek. Shall you take the test of the Heart, the Hands, or the Finger?

**You say:** `heart`




>**Dugaas Helpyre says:** So the heart it be. Bring me, foolish one, an Imp Statuette, an Obsidian Amulet, and a Pulsating Ruby. Perhaps then, you shall find your reward.

**You say:** `hands`




>**Dugaas Helpyre says:** The test of the Hands it shall be. Bring me a Gorgon's Head, some Aged Nectar, a Glowing Black Pearl, and an Efreeti's Great Staff. When you return, I shall reward you for your deeds, assuming you live through the experience. Hahaha!

**You say:** `finger`




>**Dugaas Helpyre says:** The finger. Needed for nearly every casting you shall ever hope to produce, it truly is the most powerful creation. Should you bring me a White Spiroc Feather, a Nebulous Ruby, and the Ring of Veeshan, I shall reward you with power that you can just now begin to comprehend.
end

## Turn-Ins



if( **You turn in:** [Imp Statuette](/item/20953), [Obsidian Amulet](/item/20786), [Pulsating Ruby](/item/20787)) then 







>**Dugaas Helpyre says:** Haha! So you lived! Take this and be gone!


 **You receive:**  [Sphinx Heart Amulet](/item/14560) (+100000 exp)


**Dugaas Helpyre despawns.**

elseif( **You turn in:** [Gorgon Head](/item/20790), [Aged Nectar](/item/20967), [Glowing Black Pearl](/item/20791), [Efreeti Great Staff](/item/20792)) then 



>**Dugaas Helpyre says:** Haha! So you lived! Take this and be gone!


 **You receive:**  [Gorgon Head Staff](/item/11689) (+100000 exp)


**Dugaas Helpyre despawns.**

elseif( **You turn in:** [White Spiroc Feather](/item/20960), [Nebulous Ruby](/item/20788), [Ring of Veeshan](/item/20789)) then 



>**Dugaas Helpyre says:** Haha! So you lived! Take this and be gone!


 **You receive:**  [Band of Wailing Winds](/item/27713) (+100000 exp)


**Dugaas Helpyre despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Dugaas Helpyre despawns.**




