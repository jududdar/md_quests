# High Armsman Trukhanah
## Dialog

local qglobals = eq.get_qglobals(e.other);

**You say:** `Hail`



>**High Armsman Trukhanah says:** Well met, friend.  May I be of assistance?

**You say:** `application`



>**High Armsman Trukhanah says:** Luckily for you someone found it.


**You receive:**  [Application for Citizenship](/item/2873)

**You say:** `cloak`



>**High Armsman Trukhanah says:** Someone found this stuck in the top of a palm tree in the center of the plaza. I don't even want to know how it got there, just try not to lose it this time.


**You receive:**  [Initiate's Cloak of Shar Vahl](/item/2878)
end

## Turn-Ins



local text = "This item, by itself, means nothing to me.";



if **You turn in:** [A Khala Dun Guild Summons](/item/18553)


>**High Armsman Trukhanah says:** Good Soandso. I am pleased to see you. You have come of age and it is time for you to register as a citizen of Shar Vahl. Your invitation indicates that the Khala Dun, defenders of our society, have noticed you and consider your potential to be worthy of our training. First, take this application to Registrar Bindarah and return to me with proof of your citizenship.


>**High Armsman Trukhanah says:** I know that you may be nervous right now... after all, this should be a very exciting first step for you.  If you happen to get lost while looking for the registrar, just ask one of the other citizens or guards for directions.  They will most likely know where to find the place or person that you are looking for.


eq.set_global("Shar_Vahl_Cit","1",5,"F");


 **You receive:** None 

elseif **You turn in:** [Notarized Application](/item/2897), [Acrylia Slate of Shar Vahl](/item/2877)


>**High Armsman Trukhanah says:** Congratulations Soandso! Welcome to your new life as an official citizen of Shar Vahl. This cloak symbolizes your commitment to serving this people through continuous self-improvement. For now, you must strenghten yourself until you become worthy to train in the way of the Khala Dun. Show your acylia slate to Guard Hebijeb. He will direct you further. May the spirits of our ancestors be your guide.


eq.set_global("Shar_Vahl_Cit","7",5,"F");


 **You receive:** None 

**This NPC *should* return incorrect items given.**
