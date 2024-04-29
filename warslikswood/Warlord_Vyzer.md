# Warlord Vyzer
## Dialog

**You say:** `hail`



>**Warlord Vyzer says:** Greetings, small one! You should not waste your time in the safety of the troopers' patrols. Go forth into the land and earn your stripes in battle. Become a greater asset to the Iksar empire.

**You say:** `thieves`



>**Warlord Vyzer says:** Never mind how the book was taken, just go find the goblin thieves that did the deed.

**You say:** `trooper reporting for duty`



>**Warlord Vyzer says:** Welcome to my garrison, Trooper Soandso. Lucky for you that you do not serve the inferior swamp garrison. They lose more troopers than any legion unit. You have come just in time. We need you to take this pack and fill it with goblin warlord warbeads. Combine the beads in the pack and return it to me.


**You receive:**  [Woods Garrison Pack](/item/17042)
end

## Turn-Ins



if( **You turn in:** [Note to Iksar Lord](/item/18210)) then


>**Warlord Vyzer says:** I am glad to see they have sent a strong new recruit. I have a task for you which will require you to recover a few pages of a certain poem I once wrote. I never should have written of such weak-minded things, but the pages were stolen from me before I could destroy them. Take this poem binder and find the [thieves]. When you combine the pages in the binder, it will magically lock and you may return it to me for your prize, the geozite tool.


 **You receive:**  [Book Binder](/item/17995) 

elseif( **You turn in:** [magically locked poem](/item/12667)) then


>**Warlord Vyzer says:** Great work!! You have saved me from disgrace. I reward you with the geozite tool. You may find its purpose within Cabils' warriors guild. A true Iksar warrior should always have one.


* __Faction:__ [Cabilis Residents](/faction/440) (5)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


* __Faction:__ [Scaled Mystics](/faction/445) (1)


* __Faction:__ [Swift Tails](/faction/444) (1)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (1)


 **You receive:**  [Geozite Tool](/item/12657) (+1000 exp)

elseif( **You turn in:** [Four Warbeads](/item/12912)) then


>**Warlord Vyzer says:** Great job, Trooper Soandso. Such a warrior would serve the empire better as a legionnaire and not a trooper. I shall recommend you for the rank of legionnaire.


* __Faction:__ [Cabilis Residents](/faction/440) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


* __Faction:__ [Scaled Mystics](/faction/445) (2)


* __Faction:__ [Swift Tails](/faction/444) (2)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (2)


 **You receive:**  [Legionnaire Recommendation](/item/18072) (+2000 exp)

**This NPC *should* return incorrect items given.**





