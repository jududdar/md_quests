# Garuc Anehm
## Dialog

**You say:** `Hail`



if **Faction** >= Indifferent then 



>**Garuc Anehm says:** Welcome to the Shrine of Bertoxxulous! You appear to be [new to the shrine]. I do not remember seeing you around.


else



>**Garuc Anehm says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `new to the shrine`



if **Faction** >= Indifferent then



>**Garuc Anehm says:** New blood to spread Bertoxxulous' disease? We presently need the help of a [young shadowknight]. There are certain deeds which must be carried out.


else



>**Garuc Anehm says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `young shadowknight`



if **Faction** >= Indifferent then



>**Garuc Anehm says:** Then let your supreme task be the extermination of the Priests of Life. Know that they threaten the will of our Lord Bertoxxulous. For every fallen paladin and cleric of the Temple of Life. you shall rise within our ranks.  So... do you [loathe paladins]?


else



>**Garuc Anehm says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `loathe paladins`



if **Faction** >= Indifferent then



>**Garuc Anehm says:** As do we all. The paladins of Qeynos come from either the Hall of Thunder or the Temple of Life. We have put a bounty upon their heads. Destroy these knights and return either the Order of Thunder or the prayer beads of these inferior men. There has even been a report from [Commander Kane].


else



>**Garuc Anehm says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `commander kane`



if **Faction** >= Indifferent then



>**Garuc Anehm says:** Kane Bayle is the Commander of the Qeynos Guard. He has found it advantageous to befriend the Bloodsabers. We share a [common goal]. He assists us in many ways. He has some new information to reveal.  Go and tell him you are a Bloodsaber. Do not speak with him while he is [on duty]!


else



>**Garuc Anehm says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `common goal`



if **Faction** >= Indifferent then



>**Garuc Anehm says:** Kane Bayle and the leaders of this shrine all wish to overthrow the rule of Antonius Bayle. He, for power, and we for the glory of Bertoxxulous. From this city, our diseased lord shall appear and tread across the land spitting death from his mouth and deforming the land. His glory shall be eternal!


else



>**Garuc Anehm says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!



**You say:** `on duty`



if **Faction** >= Indifferent then



>**Garuc Anehm says:** Kane is quartered within the gatehouse of Qeynos while on duty. At times he can also be found within this shrine.


else



>**Garuc Anehm says:** The lair of the Bloodsabers is no place for you...  begone, or be dead!


end

## Turn-Ins





if **Faction** >= Indifferent and  **You turn in:** [Hurrietas Bloody Dress](/item/13134)) then 


>**Garuc Anehm says:** Hahaha.. I see you actually killed a respected, well-known citizen of Qeynos. No loss for them, but you are certainly a gain for our shrine. Maybe this shall do you some good. If not now, then surely later. You may need it when the Qeynos Guards hunt you down.







* __Faction:__ [Bloodsabers](/faction/221) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:** eq.ChooseRandom( [Rats Foot Necklace](/item/1053), [Patchwork Tunic](/item/2104), 2106, 2108, 2111, 2112,  [Rat Shaped Ring](/item/13301), 15235) (+500 exp)

elseif **Faction** >= Indifferent and  **You turn in:** [Busted Prayer Beads](/item/13908)) then 


>**Garuc Anehm says:** You fool! Brother Trintle was our mole within the Priests of Life. Now you have killed him. For this you shall die!







* __Faction:__ [Bloodsabers](/faction/221) (-50)


* __Faction:__ [Guards of Qeynos](/faction/262) (7)


* __Faction:__ [Opal Darkbriar](/faction/296) (-5)


* __Faction:__ [Priests of Life](/faction/341) (12)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)



eq.attack(e.other:GetName())



elseif **Faction** >= Indifferent and  **You turn in:** [Prayer Beads](/item/13296)) then 


>**Garuc Anehm says:** Fine work! One less threat to our shrine. Take this. It shall help you become a greater asset to our shrine. Go forth and spread the disease.







* __Faction:__ [Bloodsabers](/faction/221) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:** eq.ChooseRandom( [Rats Foot Necklace](/item/1053), [Small Patchwork Tunic](/item/2116), [Small Tattered Gloves](/item/2122), [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Broad Sword](/item/5016), [Rusty Two Handed Sword](/item/5023), [Rusty Mace](/item/6011), [Torch](/item/13002), [Wooden Flute](/item/13001), [Rat Shaped Ring](/item/13301), [Wrist Pouch](/item/17001)) (+500 exp)



elseif **Faction** >= Indifferent and  **You turn in:** [Order of Thunder](/item/13287)) then 


>**Garuc Anehm says:** Fine work! One less threat to our shrine. Take this. It shall help you become a greater asset to our shrine. Go forth and spread the disease.







* __Faction:__ [Bloodsabers](/faction/221) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:** eq.ChooseRandom( [Rats Foot Necklace](/item/1053), [Small Patchwork Tunic](/item/2116), [Small Tattered Gloves](/item/2122), [Rusty Short Sword](/item/5013), [Rusty Axe](/item/5014), [Rusty Broad Sword](/item/5016), [Rusty Two Handed Sword](/item/5023), [Rusty Mace](/item/6011), [Torch](/item/13002), [Wooden Flute](/item/13001), [Rat Shaped Ring](/item/13301), [Wrist Pouch](/item/17001)) (+500 exp)





**This NPC *should* return incorrect items given.**






