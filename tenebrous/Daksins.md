# Daksins


## Dialog

**You say:** `hail`



>**Daksins says:** Hello traveller, what brings you to these cursed mountains? If I were you I would turn back now, all that really lies ahead of you is certain death. The vampires that inhabitant these mountains are some of the fiercest and most skilled.

**You say:** `return the extract`



>**Daksins says:** I suppose I could trust you to return it to Zimloro. You have earned my trust by going and slaying this beast for me. This will help me greatly as well as I must rest in Katta for a few days to recover from the wounds I received at the hands of these monsters. Please return this bag that contains the extract along with other components that Zimloro asked me to retrieve to him. Thank you, Soandso, I am forever in your debt.


**You receive:**  [Antidote Supplies](/item/4765)
end

## Turn-Ins





if( **You turn in:** [A List of Potion Components](/item/4764)) then


>**Daksins says:** I see you were sent by my friends from back home. I understand that they are very worried about me but they must understand that I am doing this to help my sister and anyone else infected by this horrible beasts. If only I could receive some help in collecting a vampyre blood extract sample I could return it home along with the other components that Zimloro decribes in this letter.





* __Faction:__ [House of Stout](/faction/1512) (25)


* __Faction:__ [Traders of the Haven](/faction/1508) (2)


 **You receive:** 0 (+5000 exp)

elseif( **You turn in:** [Vampyre Blood](/item/2693)) then


>**Daksins says:** The blood of one of the cursed! You have done it, Soandso. You must be a very skilled fighter to have bested one of these vile creatures. All that needs to be done now is to return this extract along with the other antidote supplies that I have prepared to Zimloro. Will you return this extract?





* __Faction:__ [House of Stout](/faction/1512) (25)


* __Faction:__ [Traders of the Haven](/faction/1508) (2)


 **You receive:** 0 (+5000 exp)

**This NPC *should* return incorrect items given.**
