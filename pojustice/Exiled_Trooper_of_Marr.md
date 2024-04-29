# Exiled Trooper of Marr
## On NPC Spawn

**Set a timer** named *depop* for 120 seconds

**Set a timer** named *fd* for 0 seconds

## Timer(s)

if(e.timer == "depop") then


**Exiled Trooper of Marr despawns.**

elseif(e.timer == "fd") then


**Stop timer** named *fd*


e.self:SetAppearance(3); 
end

## Turn-Ins





if( **You turn in:** [Box of Souls](/item/29281)) then


 **You receive:** GiveAll( [Soul Sphere](/item/29292), [Box of Souls](/item/29281)) 

**This NPC *should* return incorrect items given.**
