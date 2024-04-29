# Milea Clothspinner
## Dialog

if **Faction** >= Indifferent then


**You say:** `hail`




>**Milea Clothspinner says:** Hail, fellow adventurer. Are you [from Qeynos] or from [somewhere else]?


**You say:** `qeynos`




>**Milea Clothspinner says:** A great city. I was born there. I trained in the [Hall of Steel] my whole life to become a warrior. I have a sister who still calls Qeynos home.


**You say:** `hall of steel`




>**Milea Clothspinner says:** The Hall of Steel is the training ground for the greatest warriors of Antonica. I was trained by Ebon Strongbear. Now I travel the lands of Norrath. Maybe the bards will write songs of us both one day. To be an adventurer is the only way to truly live!


**You say:** `somewhere else`




>**Milea Clothspinner says:** Too bad. It is a good city to hail from. Safe from evil. I grew up there and found it quite peaceful. I trained at the [Hall of Steel].


**You say:** `kane`




>**Milea Clothspinner says:** Kane Bayle and I were students together at the Hall of Steel. He was quite a swordsman. The only men in Qeynos who could best him were Ebon Strongbear and his own brother, Antonius.


**You say:** `antonius`




>**Milea Clothspinner says:** Antonius Bayle is the ruler of the kingdom of Qeynos. Many lands look to Qeynos for protection and backing. Kane is captain of the Qeynos Guards. Two brothers working hand in hand to unite a world.


**You say:** `nerissa`




>**Milea Clothspinner says:** Nerissa Clothspinner is my sister. She is all the family I have left. I hated to leave Qeynos, but my soul yearned for adventure. I am sure she is safe, though. I had my old friend Kane Bayle promise to watch over her.


else


>**Milea Clothspinner says:** As a member of the Steel Warriors I cannot abide you. Please leave before you force me to bloody my blade.


end

## Turn-Ins




if **Faction** >= Indifferent and  **You turn in:** [A Tattered Note](/item/18801)) then


>**Milea Clothspinner says:** My sister is in danger. She is all the family I have left. I shall be on my way soon. Please take her my handkerchief, so she knows you have contacted me. Thank you. I am thankful Nerissa ran into you. I just wonder why she did not tell Kane about her suspicions.


 


* __Faction:__ [Steel Warriors](/faction/311) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Knights of Truth](/faction/281) (2)


 **You receive:**  [Monogrammed Cloth](/item/13302) (+500 exp)


**Spawn NPC:**  [\#Guard Elias](/npc/15193) at (**y:** -1870, **x:** -5521)

elseif **Faction** >= Amiable and  **You turn in:** [Sealed Note](/item/18934)) then 


>**Milea Clothspinner says:** Oh great!! I thought I'd saw that last of Plagus, or as all the women in the Steel Warriors called him, the Plague. Please do not tell him where I am. It must have been a long journey for you. Here. A little something for your wasted trip. I found it on the ground. Have fun going back to Freeport.


 


* __Faction:__ [Steel Warriors](/faction/311) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Knights of Truth](/faction/281) (1)


 **You receive:** eq.ChooseRandom( [Cloth Shawl](/item/1005), [Backpack](/item/17005), [Small Lantern](/item/13003), [Grizzly Hide Cloak](/item/2910), [Fur Lined Shoes](/item/1037), [Damask Cap](/item/1331)) (+500 exp)

**This NPC *should* return incorrect items given.**

## Signals

if(e.signal == 1) then


>**Milea Clothspinner says:** Get out of here! It is time I dealt with this traitorous guard. Okay guard, let's get it on!!


**Signaled to:**  [\#Guard Elias](/npc/15193)
end



