# Kazlo Naedra
## Dialog

local fac = e.other:GetFaction(e.self);

**You say:** `hail`



>**Kazlo Naedra says:** Hail, Soandso.  I'm Kazlo Naedra of the Order of Three.  We always seem to be running out of [supplies] around here, which is, of course, very distracting to our studies.

**You say:** `blank scroll sheets`



>**Kazlo Naedra says:** These blank sheets seem harder to find every month. All the local merchants are out of them. Hopefully, one of the merchants out in Surefall will have some.

**You say:** `supplies`



if(fac < 5) then



>**Kazlo Naedra says:** Yes, we're almost out of [blank scroll sheets]. Gahlith will be very upset, unless I can replenish our inventory soon.


else



>**Kazlo Naedra says:** The Order of Three has been monitoring your recent activities, and we are appalled by you and your actions! Now, begone!

end

## Turn-Ins







if( **You turn in:** [Blank Scroll Sheets](/item/18006)) then


>**Kazlo Naedra says:** Good work, Soandso! Here's a little something for your troubles. Your quick work and loyalty will be noted by the Order of Three.


* __Faction:__ [Order of Three](/faction/342) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Bloodsabers](/faction/221) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


 **You receive:** 0 (+200 exp)

**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 10) then


>**Kazlo Naedra says:** Hey guys, you got any blank scroll sheets for sale? Or know where I could get some around here?


**Signaled to:**  [Barthal](/npc/1115)
end
