# an elven slave
## Dialog

**You say:** `hail`



>**an elven slave says:** Slavedrivers are just lackeys for the [taskmaster]. He is the real orc in charge.

**You say:** `taskmaster`



>**an elven slave says:** The taskmaster?? He is that large orc who runs around with that [bronze earring] in his ear.

**You say:** `bronze earring`



>**an elven slave says:** Yeah, a bronze earring; He wears it like a newly crowned king. If I ever had that earring I know I would stand a chance at escape.
end

## Turn-Ins






if(e.self:GetRace() == 5 and e.self:GetGender() == 0) then 


if **You turn in:** copper = 1



>**an elven slave says:** Not that!! I need key number 20!!


elseif **You turn in:** [Shackle Key 20](/item/20020)



>**an elven slave says:** Good work!! I shall be on my way. Farewell my friend!!



* __Faction:__ [Keepers of the Art](/faction/275) (2)



* __Faction:__ [King Tearis Thex](/faction/279) (1)



* __Faction:__ [Faydarks Champions](/faction/246) (1)



* __Faction:__ [The Dead](/faction/239) (-1)



 **You receive:** 0 (+800 exp)



**an elven slave despawns.**


elseif **You turn in:** [Brass Earring](/item/10351)



>**an elven slave says:** You killed the taskmaster?!  Absolutely amazing! The orcs will be fighting among themselves for power now and I can disappear in the commotion. Thanks, friend! Take this for your deeds!



 **You receive:**  [A Ragged Cloth Note](/item/18901) (+5000 exp)



**an elven slave despawns.**




elseif(e.self:GetRace() == 5 and e.self:GetGender() == 1) then 


if **You turn in:** copper = 1



>**an elven slave says:** Please!! I need a key with a number 21!!


elseif **You turn in:** [Shackle Key 21](/item/20021)



>**an elven slave says:** Good work!! I shall be on my way. Farewell my friend!!



* __Faction:__ [Keepers of the Art](/faction/275) (2)



* __Faction:__ [King Tearis Thex](/faction/279) (1)



* __Faction:__ [Faydarks Champions](/faction/246) (1)



* __Faction:__ [The Dead](/faction/239) (-1)



 **You receive:** 0 (+800 exp)



**an elven slave despawns.**


elseif **You turn in:** [Brass Earring](/item/10351)



>**an elven slave says:** You killed the taskmaster?!  Absolutely amazing! The orcs will be fighting among themselves for power now and I can disappear in the commotion. Thanks, friend! Take this for your deeds!



 **You receive:**  [A Torn Drawing](/item/18902) (+5000 exp)



**an elven slave despawns.**




elseif(e.self:GetRace() == 4 and e.self:GetGender() == 0) then 


if **You turn in:** copper = 1



>**an elven slave says:** Not that!! I need key number 18!!


elseif **You turn in:** [Shackle Key 18](/item/20018)



>**an elven slave says:** Good work!! I shall be on my way. Farewell my friend!!



* __Faction:__ [Emerald Warriors](/faction/326) (2)



* __Faction:__ [Indigo Brotherhood](/faction/270) (-1)



* __Faction:__ [Merchants of Felwithe](/faction/325) (1)



* __Faction:__ [Kelethin Merchants](/faction/276) (1)



 **You receive:** 0 (+800 exp)



e.other:GiveCash(0,7,3,0);



**an elven slave despawns.**


elseif **You turn in:** [Brass Earring](/item/10351)



>**an elven slave says:** You killed the taskmaster?!  Absolutely amazing! The orcs will be fighting among themselves for power now and I can disappear in the commotion. Thanks, friend! Take this for your deeds!



 **You receive:**  [A Tattered Cloth Note](/item/18903) (+5000 exp)



**an elven slave despawns.**




elseif(e.self:GetRace() == 4 and e.self:GetGender() == 1) then 


if **You turn in:** copper = 1



>**an elven slave says:** Please!! I need a key with a number 19!!


elseif **You turn in:** [Shackle Key 19](/item/20019)



>**an elven slave says:** Good work!! I shall be on my way. Farewell my friend!!



* __Faction:__ [Emerald Warriors](/faction/326) (2)



* __Faction:__ [Indigo Brotherhood](/faction/270) (-1)



* __Faction:__ [Merchants of Felwithe](/faction/325) (1)



* __Faction:__ [Kelethin Merchants](/faction/276) (1)



 **You receive:** 0 (+800 exp)



**an elven slave despawns.**


elseif **You turn in:** [Brass Earring](/item/10351)



>**an elven slave says:** You killed the taskmaster?!  Absolutely amazing! The orcs will be fighting among themselves for power now and I can disappear in the commotion. Thanks, friend! Take this for your deeds!



 **You receive:**  [A Faded Wedding Cloth](/item/18904) (+5000 exp)



**an elven slave despawns.**




**This NPC *should* return incorrect items given.**
;