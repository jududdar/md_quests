# Royal Armorer Slade


## Dialog

**You say:** `hail`



if **Faction** >= Warmly then



>**Royal Armorer Slade says:** Welcome, Soandso. I'm Slade, Royal Armorer to the Dain and his personal guardsmen. I've heard yer name once or twice in these halls and apparently ye've earned the respect of my people. In light of that I'm willin ta offer my [services] to you if'n ye need them.


elseif **Faction** >= Indifferent then



>**Royal Armorer Slade says:** I'm sorry, Soandso, while I've heard good things about ye you've yet to prove yerself enough to my people to earn my services.


else



>**Royal Armorer Slade says:** Leave me be, " .. e.other:Race() .. ". I have no reason to trust you yet.


**You say:** `service`



if **Faction** >= Warmly then



>**Royal Armorer Slade says:** If'n ye've had the fortune to earn any of the plate helms that are made by my people in the city then I can use my skills to custom fit and detail it for a " .. e.other:Race() .. " of yer like. I can do this fer the Dark Runed Crown, the Runed Protector's Helm, the Resonant Helm, the Crown of Forbidden Rites, Crown of the Kromzek Kings, Frostreaver's Velium Crown, Cowl of Mortality, and the Champions Crown. Simply hand me one of these and I'll do the work for you.


elseif **Faction** >= Indifferent then



>**Royal Armorer Slade says:** I'm sorry, Soandso, while I've heard good things about ye you've yet to prove yerself enough to my people to earn my services.


else



>**Royal Armorer Slade says:** Leave me be, " .. e.other:Race() .. ". I have no reason to trust you yet.

end

## Turn-Ins





if( **Faction is** >= Kindly) then 


if( **You turn in:** [Champion's Crown](/item/31084)) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 **You receive:**  [Custom Champion's Crown](/item/31519) 


elseif( **You turn in:** [Cowl of Mortality](/item/26025)) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 **You receive:**  [Custom Cowl of Mortality](/item/2612) 


elseif( **You turn in:** [Crown of Forbidden Rites](/item/31042)) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 **You receive:**  [Custom Crown of Forbidden Rites](/item/31518) 


elseif( **You turn in:** [Crown of the Kromzek Kings](/item/25194)) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 **You receive:**  [Custom Crown of the Kromzek Kings](/item/2611) 


elseif( **You turn in:** [Dark Runed Crown](/item/31000)) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 **You receive:**  [Custom Dark Runed Crown](/item/31515) 


elseif( **You turn in:** [Frostreaver's Velium Crown](/item/30507)) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 **You receive:**  [Custom Frostreavers Velium Crown](/item/2610) 


elseif( **You turn in:** [Resonant Helm](/item/31035)) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 **You receive:**  [Custom Resonant Helm](/item/31517) 


elseif( **You turn in:** [Runed Protector's Helm](/item/31021)) then



>**Royal Armorer Slade says:** Here you are Soandso. Ah, a perfect fit! May it serve you well.



 **You receive:**  [Custom Runed Protector's Helm](/item/31516) 


**This NPC *should* return incorrect items given.**

