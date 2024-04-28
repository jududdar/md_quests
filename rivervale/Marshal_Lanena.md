# Marshal Lanena







## Dialog

local fac = e.other:GetFaction(e.self);


**You say:** `hail`



>**Marshal Lanena says:** Hello. Soandso.  I am Lanena Wickystick, marshal of all Vale concerns.  If there are any troubles brewing in our fine town which concern the Guardians of the Vale, please inform me.  You must be a [new deputy] or are you an [outsider]?

**You say:** `new deputy`



if **Faction** >= Amiable then 



>**Marshal Lanena says:** It is good to see such fine stock in the ranks of the Guardians.  Being new, there is much to learn, in battle and in life itself.  If you are not presently obligated, we have need of you here in the hollow.  There seems to be a [small problem].


elseif **Faction** >= Indifferent then



>**Marshal Lanena says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.


else



>**Marshal Lanena says:** How can you expect to just waltz into Guardian Stronghold and expect to gather information?! Consider yourself lucky I don't command the Guardian of the Vale deputies to show you the sharpness of their blades!


**You say:** `outsider`



>**Marshal Lanena says:** Well, then!! You should not be in here.  This place is restricted to all outsiders.  You will leave at once!  Thank you and good day.

**You say:** `small problem`



if **Faction** >= Amiable then



>**Marshal Lanena says:** For months, Fiddy Bobick has petitioned the marshals to assist him with a problem he has.  With the addition of new deputies such as yourself, we can now give him the assistance he requires.  Just go down to Bobick's shop near the lake.  Tell him I sent you.


elseif **Faction** >= Indifferent then



>**Marshal Lanena says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.


else



>**Marshal Lanena says:** How can you expect to just waltz into Guardian Stronghold and expect to gather information?! Consider yourself lucky I don't command the Guardian of the Vale deputies to show you the sharpness of their blades!


**You say:** `rantho rapier`



>**Marshal Lanena says:** The Rantho Rapier was crafted by the great blacksmith Rantho Goobler.  It was designed for use by the warriors of the wee folk.  With its light weight and special two-hand hilt, it becomes a formidable weapon in the hands of our younger deputies.  Only a [new deputy] has the right to earn one.
end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Piranha Tooth](/item/13929)


>**Marshal Lanena says:** What was I thinking?!! Piranha are coming downstream and eating our supply of fish! We have never had a problem like this!!  Where are these little beasts coming from?  For now we must collect more. Take this bag. Collect enough teeth to fill the bag. Don't worry, if it takes a while I shall reward you with the [Rantho Rapier].  We will need to examine the teeth.


* __Faction:__ [Guardians of the Vale](/faction/263) (2)


* __Faction:__ [Mayor Gubbin](/faction/286) (1)


* __Faction:__ [Storm Reapers](/faction/355) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (1)


* __Faction:__ [Dreadguard Outer](/faction/334) (-1)


 **You receive:** None 

elseif **Faction** >= Amiable and  **You turn in:** [Bag of Piranha Teeth](/item/12155)


>**Marshal Lanena says:** Fine work. We shall continue to study these and shall determine if we need to seek the source.


* __Faction:__ [Guardians of the Vale](/faction/263) (10)


* __Faction:__ [Mayor Gubbin](/faction/286) (1)


* __Faction:__ [Storm Reapers](/faction/355) (1)


* __Faction:__ [Merchants of Rivervale](/faction/292) (1)


* __Faction:__ [Dreadguard Outer](/faction/334) (-1)


 **You receive:** None 

elseif **Faction** >= Indifferent then


>**Marshal Lanena says:** You are in good standing with the Guardians of the Vale. Continue with your good work and then we may speak.

else


>**Marshal Lanena says:** How can you expect to just waltz into Guardian Stronghold and expect to gather information?! Consider yourself lucky I don't command the Guardian of the Vale deputies to show you the sharpness of their blades!

**This NPC *should* return incorrect items given.**


