# Chief Kalan
## Dialog

**You say:** `hail`



>*Chief Kalan nods respectfully and says 'Welcome to Siren Bay strange one. These beaches belong to my people, the Othmir. You are welcome in our villages as long as you do not cause trouble and are willing to either assist the shellfish collectors provide nourishment or aid the warriors defending the beaches.'*

**You say:** `aid the warriors`



>**Chief Kalan says:** There are many creatures that would prey on my people if it were not for the dedication of our warriors. The Bulthar and Ulthork often invade our territory and prey on our shellfish collectors. They are wasteful creatures and take more than they could possibly eat from the sacred seas.

**You say:** `bulthar`



>**Chief Kalan says:** The Bulthar are sea elephant people. They are strong brutes with the intelligence of a clam. There is no reasoning with the savages since they seem to only understand their territorial instincts. There is a small herd of them that has taken up residence on the rocky beach beneath the lonely tower and have already injured many of our shellfish collectors. I will reward you for the trunks of every two brutes that you slay.

**You say:** `ulthork`



>**Chief Kalan says:** The Ulthork are walrus people. They are just as territorial and brutish as the Bulthar but are slightly more intelligent. They seem to be jealous of my people's prosperity and occasionally lead raiding parties onto our beaches. Our craftsman use the tusks of the slain Ulthork to carve ivory totems of praise to the ocean lord. I will gladly barter for no less than four pairs of Ulthork tusks.
end

## Turn-Ins



local text1 = "I will barter for no less than four pairs of Ulthork tusks.";




if **You turn in:** [Ulthork Tusks](/item/24874), [Ulthork Tusks](/item/24874), [Ulthork Tusks](/item/24874), [Ulthork Tusks](/item/24874)


>**Chief Kalan says:** Many thanks to you, strange one. Our craftsman will be pleased. They have been in need of a new bundle of ivory.


* __Faction:__ [Othmir](/faction/432) (10)


* __Faction:__ [Ulthork](/faction/431) (-1)


 **You receive:** eq.ChooseRandom( [Black Sapphire](/item/10036), [Blue Diamond](/item/22503), [Crystallized Sulfur](/item/16976), [Diamond](/item/10037), [Fire Emerald](/item/10033), [Fire Emerald Ring](/item/10049), [Fire Opal](/item/10031), [Jacinth](/item/10053), [Ruby](/item/10035), [Ruby Crown](/item/10051), [Sapphire](/item/10034), [Sapphire Necklace](/item/10050), [Star Ruby](/item/10032), [Star Ruby Earring](/item/10048)) (+1000 exp)

elseif **You turn in:** [Bulthar Trunk](/item/30068)


>**Chief Kalan says:** With the Bulthar herd leader dead we can hope that they will move on to less occupied waters.


* __Faction:__ [Othmir](/faction/432) (5)


* __Faction:__ [Ulthork](/faction/431) (-1)


 **You receive:**  [Runed Othmir Spear](/item/22817) (+5000 exp)

elseif **You turn in:** [Bulthar Trunk](/item/30067), [Bulthar Trunk](/item/30067)


>**Chief Kalan says:** Such wasteful creatures the Bulthar are. It is a shame they are not intelligent enough to realize the harm they do to the very oceans that sustain them.


* __Faction:__ [Othmir](/faction/432) (2)


* __Faction:__ [Ulthork](/faction/431) (-1)


 **You receive:** eq.ChooseRandom( [Black Sapphire](/item/10036), [Blue Diamond](/item/22503), [Crystallized Sulfur](/item/16976), [Diamond](/item/10037), [Fire Emerald](/item/10033), [Fire Emerald Ring](/item/10049), [Fire Opal](/item/10031), [Jacinth](/item/10053), [Ruby](/item/10035), [Ruby Crown](/item/10051), [Sapphire](/item/10034), [Sapphire Necklace](/item/10050), [Star Ruby](/item/10032), [Star Ruby Earring](/item/10048)) (+1000 exp)

**This NPC *should* return incorrect items given.**
