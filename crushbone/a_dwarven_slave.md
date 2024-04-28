# a dwarven slave
## Dialog

**You say:** `hail`



>**a dwarven slave says:** Slavedrivers are just lackeys for the [taskmaster]. He is the real orc in charge.

**You say:** `taskmaster`



>**a dwarven slave says:** The taskmaster?? He is that large orc who runs around with that [bronze earring] in his ear.

**You say:** `bronze earring`



>**a dwarven slave says:** Yeah, a bronze earring; He wears it like a newly crowned king. If I ever had that earring I know I would stand a chance at escape.
end

## Turn-Ins






if(e.self:GetRace() == 8 and e.self:GetGender() == 0) then 


if **You turn in:** copper = 1



>**a dwarven slave says:** No, no!! I do not need this!! Get me key number 16!!


elseif **You turn in:** [Shackle Key 16](/item/20016)



>**a dwarven slave says:** Good work!! I shall be on my way. Farewell my friend!!



* __Faction:__ [Clerics of Underfoot](/faction/227) (2)



* __Faction:__ [Kazon Stormhammer](/faction/274) (2)



* __Faction:__ [Miners Guild 249](/faction/293) (1)



 **You receive:** 0 (+800 exp)



**a dwarven slave despawns.**


elseif **You turn in:** [Brass Earring](/item/10351)



>**a dwarven slave says:** You killed the taskmaster?!  Absolutely amazing! The orcs will be fighting among themselves for power now and I can disappear in the commotion. Thanks, friend! Take this for your deeds!



 **You receive:**  [A Worn Rune](/item/18905) (+5000 exp)



**a dwarven slave despawns.**




elseif(e.self:GetRace() == 8 and e.self:GetGender() == 1) then 


if **You turn in:** copper = 1



>**a dwarven slave says:** What is this!!? Get me key number 17!!


elseif **You turn in:** [Shackle Key 17](/item/20017)



>**a dwarven slave says:** Good work!! I shall be on my way. Farewell my friend!!



* __Faction:__ [Storm Guard](/faction/312) (2)



* __Faction:__ [Kazon Stormhammer](/faction/274) (1)



* __Faction:__ [Miners Guild 249](/faction/293) (1)



* __Faction:__ [Merchants of Kaladim](/faction/290) (1)



* __Faction:__ [Craknek Warriors](/faction/232) (-1)



 **You receive:** 0 (+800 exp)



**a dwarven slave despawns.**


elseif **You turn in:** [Brass Earring](/item/10351)



>**a dwarven slave says:** You killed the taskmaster?!  Absolutely amazing! The orcs will be fighting among themselves for power now and I can disappear in the commotion. Thanks, friend! Take this for your deeds!



 **You receive:**  [A Small Wood Carving](/item/18906) (+5000 exp)



**a dwarven slave despawns.**




**This NPC *should* return incorrect items given.**
;