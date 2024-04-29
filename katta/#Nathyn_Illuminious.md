# Nathyn Illuminious
## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);


**You say:** `hail`



>**Nathyn Illuminious says:** I do not believe that I invited you to enter my home. If this is not a visit concerning a pressing issue that may pique my concern then please remove yourself from these premises. I am a very busy man and have no time to waste on the concern of commoners.

**You say:** `valdanov zefeer`



>**Nathyn Illuminious says:** Valdanov Zevfeer was a talented alchemist from Shadow Haven with whom I had many dealings. He would bring me components for my enchantment research from all the various environments here on Luclin. Since Valdanov had been such a valuable aid to me in the past I decided to return the favor and allowed him residence within my abode and helped to further fund his research as long as he assisted me in my own enchantment studies. He has since left to continue to pursue his own interests and I have not heard from him in [quite some time].

**You say:** `quite some time`



>**Nathyn Illuminious says:** Valdanov departed many years ago. He had become dangerously obsessive with his research of vampyre physiology and the effects of various alchemical formulae on the undead creatures. His obsession began when a traveler arrived in Katta Castellum speaking of a Vah Shir vampyre. Valdanov began leaving the safety of the city frequently in search of this undead Vah Shir and for questionable alchemical reagents with which he insisted on testing on [captured vampyres] being studied by the Magus Conlegium.

**You say:** `captured vampyres`



>**Nathyn Illuminious says:** After an unfortunate mishap with an escaped vampyre in the city the Magus Conlegium and the Validus Custodus declared that no vampyres shall ever again enter the city of Katta Castellum and only their ashes or blood may be studied under the careful observation of the Magus Conlegium. I am very sorry but I have some pressing business I must attend to and I'm afraid I have nothing more to offer. You may take this information back to Magistrate Phenic as he has requested.


 **You receive:**  [Report of Nathyns Questioning](/item/31755) 


eq.delete_global("first_badge_nathyn");
end

## Turn-Ins





if( **You turn in:** [Katta Castellum Badge of Service](/item/31752)) then


>**Nathyn Illuminious says:** Ahh I see you're assisting Phenic. Perhaps looking into more information on [Valdanov Zefeer]?


eq.set_global("first_badge_nathyn","1",0,"F");


 **You receive:**  [Katta Castellum Badge of Service](/item/31754) 

**This NPC *should* return incorrect items given.**
