# Councilman Taldarius

## Dialog

**You say:** `hail`



>*Councilman Taldarius regards you, and grins. 'Greetings, Soandso. I am Councilman Taldarius, mighty Paladin of Mithaniel Marr and Guardian of the City of Tanaan! If you cannot find what you are looking for here in the Myrist library, I most certainly can add it to my list of things to look for in the Planes. Unfortunately, I am quite busy at the moment, planning my next trip to the Elemental Planes. I believe my aid may have some tasks he could use help with. That is, if you are skilled enough.'*

**You say:** `marked runed signet`



>**Councilman Taldarius says:** I see you have helped Grimel immensely. He would not have given up his signet very easily. I cannot let him deprive himself of such a valuable tool. If you were to do a task for me I would grant you something I picked up in the Planes. Are you interested in the task?

**You say:** `interested in the task`



>**Councilman Taldarius says:** Very well Soandso. I warn you I will not grant this without proof that you possess a valiant spirit. You may have the trust of my aid but I still require a noble deed. Through research done by the council they have discovered something called a Hope Stone that exists in the Elemental Planes. Bring me one of these stones and the signet of Grimel. Fear not I shall reward you well.
end

## Turn-Ins



if( **You turn in:** [Marked Runed Signet](/item/16256), [Hope Stone](/item/16258) and not **You possess item:**  [Signet of Might](/item/16255) x 1


>**Councilman Taldarius says:** Wonderful! You have proven yourself as both a Master of the Trade as well as a valiant spirit. Take this and may it server you well! If this signet does not suffice, bring it back to me and i will exchange it for one more attuned to your needs.


 **You receive:**  [Signet of Might](/item/16255) 

elseif( **You turn in:** [Signet of Might](/item/16255)) then 


>**Councilman Taldarius says:** I hope this is more attuned to your needs.


 **You receive:**  [Signet of  the Arcane](/item/16257) 

elseif( **You turn in:** [Signet of  the Arcane](/item/16257)) then 


>**Councilman Taldarius says:** I hope this is more attuned to your needs.


 **You receive:**  [Signet of Might](/item/16255) 

**This NPC *should* return incorrect items given.**





