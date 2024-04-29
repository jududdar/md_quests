# Lomarc
## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds
## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>**Lomarc says:** I'm sure I have a few contacts who would be very pleased with this find.


## Arrive at Waypoint Script

if(e.wp == 16 or e.wp == 43 or e.wp == 70) then


>**Lomarc says:** Psst.. Hey, you there.. Yeah, you.. You need some [blank scroll sheets].. I just got a special shipment of things in.. Come on, it's just what you're looking for.. I know you.
end

## Dialog

**You say:** `hail`



if **Faction** >= Dubious then



>**Lomarc says:** Do I know you? Don't stick your nose where it don't belong. It might just get cut off.


else



>**Lomarc says:** To a wanderer of the Karanas such as myself, you are as insignificant as the dirt I walk on.


**You say:** `blank`



if **Faction** >= Dubious then



>**Lomarc says:** Blank scroll sheets, huh? You know, there seems to be a shortage of these around here lately. But, hey friend, ol' Denny-boy here would never steer you wrong. I'll sell you some for 2 gold. I know, I'm too kind.


else



>**Lomarc says:** To a wanderer of the Karanas such as myself, you are as insignificant as the dirt I walk on.


**You say:** `bandit`



if **Faction** >= Dubious then



>**Lomarc says:** My associates? Let's just say they run a small trading operation between here and [Highpass].


else



>**Lomarc says:** To a wanderer of the Karanas such as myself, you are as insignificant as the dirt I walk on.


**You say:** `highpass`



if **Faction** >= Dubious then



>**Lomarc says:** Highpass Hold... it's a good day's journey from here... And if I were you, I wouldn't travel it alone or at night.


else



>**Lomarc says:** To a wanderer of the Karanas such as myself, you are as insignificant as the dirt I walk on.

end

## Turn-Ins



if( **You turn in:** gold = 2) then


>**Lomarc says:** Yeah, well, these are pretty hard to come by. In fact, these came all the way from Odus. Enjoy, and tell your buddies.





* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)




* __Faction:__ [Merchants of Qeynos](/faction/291) (-1)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)




* __Faction:__ [Guards of Qeynos](/faction/262) (-1)



* __Faction:__ [Kane Bayle](/faction/273) (1)







 **You receive:**  [Blank Scroll Sheets](/item/18006) (+100 exp)

elseif( **You turn in:** [Lomarc's Payment](/item/18793)) then 


>**Lomarc says:** What the heck is this?!? No money at all? You'll pay for this, you back-stabbing knave!


**Lomarc attacks you.**

**This NPC *should* return incorrect items given.**
