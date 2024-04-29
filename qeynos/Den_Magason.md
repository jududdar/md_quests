# Den Magason
## Arrive at Waypoint Script

if(e.wp == 16 or e.wp == 43 or e.wp == 70) then


>**Den Magason says:** Psst.. Hey, you there.. Yeah, you.. You need some [blank scroll sheets].. I just got a special shipment of things in.. Come on, it's just what you're looking for.. I know you.
end

## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then




>**Den Magason says:** Oh, hey there.. How ya doing? My name's Den. I work for ol' [Rohand] here, unloading the [shipments] that come in from overseas.


else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!


**You say:** `rohand`



if **Faction** >= Apprehensive then



>**Den Magason says:** Ol' Captain Rohand is the owner of the Mermaid's Lure. He trades goods with sailors and sea [merchants]. I think that old man was even born at sea.. And he's got more stories than fish have scales.



else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!


**You say:** `shipments`



if **Faction** >= Apprehensive then



>**Den Magason says:** Yeah.. We get merchants and traders with goods from here to [Odus].



else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!


**You say:** `blank scroll sheets`



if **Faction** >= Apprehensive then



>**Den Magason says:** Blank scroll sheets, huh? You know, there seems to be a shortage of these around here lately. But, hey friend, ol' Denny-boy here would never steer you wrong. I'll sell you some for 2 gold. I know, I'm too kind.


else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!


**You say:** `Odus`



if **Faction** >= Apprehensive then



>**Den Magason says:** Odus? I've never been there, but I hear it's a long journey.


else



>**Den Magason says:** Wha'?  Another talking rat? Your reputation with the merchants in this town has put a price on your head...  begone, before I decide to collect!

end

## Turn-Ins



local text = "Ok, good job, but I still need the other ones, too. Get the rest of them, so I can ship them all to Odus.";



if( **You turn in:** gold = 2) then


>**Den Magason says:** Yeah, well, these are pretty hard to come by. In fact, these came all the way from Odus. Enjoy, and tell your buddies.





* __Faction:__ [Circle of Unseen Hands](/faction/223) (1)




* __Faction:__ [Merchants of Qeynos](/faction/291) (-1)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)




* __Faction:__ [Guards of Qeynos](/faction/262) (-1)



* __Faction:__ [Kane Bayle](/faction/273) (1)







 **You receive:**  [Blank Scroll Sheets](/item/18006) (+100 exp)

elseif( **You turn in:** [Package for Den](/item/13784)) then


>**Den Magason says:** All right, I'll make sure this gets put on the next boat to Erudin. But now, I need a favor of you. Since I'm stuck here working the docks all day, I need someone to run out to Qeynos Hills and bring me back various pelts and skins. I got a customer in Odus who is trying to get a new shop started, and he needs some samples. Bring me back some snake scales, a high quality bear skin, a high quality wolf skin, and some bat fur. Make sure the quality is good, I can't send him rags.





* __Faction:__ [Circle of Unseen Hands](/faction/223) (10)




* __Faction:__ [Merchants of Qeynos](/faction/291) (-1)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)




* __Faction:__ [Guards of Qeynos](/faction/262) (-1)



* __Faction:__ [Kane Bayle](/faction/273) (1)




 **You receive:** 0 (+1000 exp)

elseif( **You turn in:** [Snake Scales](/item/13070), [High Quality Bear Skin](/item/13752), [High Quality Wolf Skin](/item/13755), [Bat Fur](/item/13069)) then 


>**Den Magason says:** Great... Hopefully he will like these samples, and order a lot more from me. Here's some gold for your efforts. Also, could you pass this note on to Ghil next time you talk to him? Thanks again.





* __Faction:__ [Circle of Unseen Hands](/faction/223) (20)




* __Faction:__ [Merchants of Qeynos](/faction/291) (-3)



* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (3)




* __Faction:__ [Guards of Qeynos](/faction/262) (-3)



* __Faction:__ [Kane Bayle](/faction/273) (3)




 **You receive:**  [Note for Ghil](/item/18796) (+50000 exp)


**This NPC *should* return incorrect items given.**
