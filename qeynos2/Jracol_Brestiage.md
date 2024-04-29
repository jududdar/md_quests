# Jracol Brestiage
## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds
## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>**Jracol Brestiage says:** Look what I found! I hear there's a good market for these back in Highpass.. lucky me!



local proof = 0;

## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Jracol Brestiage says:** You'd better run along, if ya know what's best for ya!


else



>**Jracol Brestiage says:** Carson hates you, and I hate you... I'd kill you where you stand, but I just polished my dagger last night.





**You say:** `lovely night for a stroll`



if **Faction** >= Apprehensive then



>**Jracol Brestiage says:** Yes, it is a lovely night for a walk, especially with a good friend. Tell me, are you a [friend]?


else



>**Jracol Brestiage says:** Carson hates you, and I hate you... I'd kill you where you stand, but I just polished my dagger last night.


**You say:** `friend`



if **Faction** >= Apprehensive then



>**Jracol Brestiage says:** My memory is a bit fuzzy. If you are a friend, prove it to me.


else



>**Jracol Brestiage says:** Carson hates you, and I hate you... I'd kill you where you stand, but I just polished my dagger last night.

end

## Turn-Ins




if( **You turn in:** [Bent Playing Card](/item/13903)) then 


>**Jracol Brestiage says:** 'Ah, good, it seems we have much in common after all. Take this back to the Circle, before the city guards come nosing around over here.


* __Faction:__ [Carson McCabe](/faction/329) (5)


* __Faction:__ [Coalition of Tradefolk Underground](/faction/336) (3)


* __Faction:__ [Ring of Scale](/faction/304) (-1)


* __Faction:__ [Highpass Guards](/faction/332) (5)


* __Faction:__ [Merchants of Highpass](/faction/331) (5)


 **You receive:**  [Sealed Note For Knargon](/item/18722) (+0 exp)

**This NPC *should* return incorrect items given.**
