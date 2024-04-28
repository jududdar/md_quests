# Master Taruun Rakutah
## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);

**You say:** `hail`



>**Master Taruun Rakutah says:** Well met, friend. May I be of assistance?

**You say:** `application`



>**Master Taruun Rakutah says:** Luckily for you someone found it.


**You receive:**  [Application for Citizenship](/item/2873)

**You say:** `cloak`



>**Master Taruun Rakutah says:** Someone found a rockhopper chewing on this in the pit. Try not to lose it this time.


**You receive:**  [Initiate's Cloak of Shar Vahl](/item/2878)
end

## Turn-Ins



local text = "This item, by itself, means nothing to me.";



if **You turn in:** [A Taruun Guild Summons](/item/18554)


>**Master Taruun Rakutah says:** Good Soandso, I am pleased to see you. You have come of age and it is time for you to register for citzenship. Your invitation indicates that the Taruun, hunters and providers of Shar Vahl, have noticed you and consider your potential to be worthy of our training. First, take this application to the Registrar Bindarah and return to me with proof of citzenship.


>**Master Taruun Rakutah says:** I know that you may be nervous right now... after all, this should be very exciting first step for you. If you happen to get lost while looking for the registrar, just ask one of the other citizens or guards for directions. They will most likely know where to find the place or person that you are looking for.


eq.set_global("Shar_Vahl_Cit","1",5,"F");


 **You receive:** None 

elseif **You turn in:** [Shadowscream Steel Boots](/item/29828)


>**Master Taruun Rakutah says:** So you're Barkhem's newest student are you? I may not have taken your word for it, but craftsmanship this fine could only be from a student of our Master Smith. Take this and fill it with Shadowscream steel boots. I need 6 pairs to outfit some of my hunters. When you've finished, return the box to me.


 **You receive:**  [Boot Case](/item/17499) 

elseif **You turn in:** [Shadowscream Boot Case](/item/29825)


>*Master Taruun Rakutah inspects the boots for a moment and looks you square in the eyes. 'This is excellent work, Soandso, you do not disappoint! Would that you could outfit all of my hunters with these boots, but I must not keep your talents all to myself. Take some change for your troubles and this seal back to Barkhem - let him know that I am very impressed with his new protege.'*


* __Faction:__ [Guardians of Shar Vahl](/faction/1513) (10)


 **You receive:**  [Rakutah's Seal](/item/29826) (+500 exp)

elseif **You turn in:** [Notarized Application](/item/2897), [Acrylia Slate of Shar Vahl](/item/2877)


>**Master Taruun Rakutah says:** Allow me to be the first to welcome you. Accept this cloak, young initiate. It is a symbol of your loyalty to our noble people. May it serve you as you serve us all. Present your acrylia slate to Harbin Gernawl and he will give you instruction. May the spirits of the beasts guide you and keep you safe.


eq.set_global("Shar_Vahl_Cit","7",5,"F");


 **You receive:** None 

**This NPC *should* return incorrect items given.**





