# Lathin Firetree
## Dialog

**You say:** `hail`



>**Lathin Firetree says:** Well met brave " .. e.other:Race() .. ". I am Lathin Firetree, Governor of Wizardry here at the Magus Conlegium. I have an abundance of research and experimentation to attend to so unless you have an issue of importance to present or are going to assist me with the research I must get back to my studies.
end

## Turn-Ins



local text = "I require the instructions from Phenic and the Autarkic Shade Lord Belt.";



if( **You turn in:** [Instructions for Lathin Firetree](/item/7270), [Autarkic Shade Lord Belt](/item/7169)) then


>**Lathin Firetree says:** Phenic wishes me to summon the Shade that is the owner of this belt for questioning. That is quite a dangerous request but it is not uncommon of Phenic to be a risk taker when it comes to his plots against the Coterie of the Eternal Night. Take this sketch and find a skilled potter to craft you a likeness of a shade from a large block of clay as a focus item for the ritual. When you have the unfired figurine fire it in a kiln with this special glaze on a High Quality Firing Sheet and return to me.


* __Faction:__ [Magus Conlegium](/faction/1504) (2)


* __Faction:__ [Katta Castellum Citizens](/faction/1502) (1)


* __Faction:__ [Validus Custodus](/faction/1503) (1)


* __Faction:__ [Seru](/faction/1483) (-1)


* __Faction:__ [Hand of Seru](/faction/1484) (-1)


* __Faction:__ [Eye of Seru](/faction/1485) (-1)


* __Faction:__ [Hand Legionnaries](/faction/1541) (-1)


 **You receive:** GiveAll( [Shade Figurine Sketch](/item/7271), [Conlegium Enchanted Glaze](/item/7272)) (+1000000 exp)

elseif( **You turn in:** [Shade Summoning Figurine](/item/7273)) then


>**Lathin Firetree says:** Excellent, this figurine will work wonderfully. A group of my best summoners is gathering on the first floor at the largest of the summoning circles to call forth the shade. Please take the figurine to Theurgus Ajeea Polaja immediately.


* __Faction:__ [Magus Conlegium](/faction/1504) (5)


* __Faction:__ [Katta Castellum Citizens](/faction/1502) (1)


* __Faction:__ [Validus Custodus](/faction/1503) (1)


* __Faction:__ [Seru](/faction/1483) (-1)


* __Faction:__ [Hand of Seru](/faction/1484) (-1)


* __Faction:__ [Eye of Seru](/faction/1485) (-1)


* __Faction:__ [Hand Legionnaries](/faction/1541) (-1)


 **You receive:**  [Shade Summoning Figurine](/item/7779) 


**Despawn NPC:**  [Theurgus Ajeea Polaja](/npc/160410)


**Despawn NPC:**  [Incantator Jak Masric](/npc/160252)


**Despawn NPC:**  [Praecantor Selis Dawneyes](/npc/160253)


**Spawn NPC:**  [\#Theurgus Ajeea Polaja](/npc/160133) at (**y:** -807, **x:** -75)


**Spawn NPC:**  [\#Praecantor Selis Dawneyes](/npc/160142) at (**y:** -808, **x:** -120)


**Spawn NPC:**  [\#Incantator Jak Masric](/npc/160160) at (**y:** -858, **x:** -97)

**This NPC *should* return incorrect items given.**
