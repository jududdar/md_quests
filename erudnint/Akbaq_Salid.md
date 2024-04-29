# Akbaq Salid



## Dialog

if ( **Faction is** >= Indifferent) then 



**You say:** `hail`




>**Akbaq Salid says:** Greetings, Soandso. I have recently returned to Erudin since hearing word of the titan spirits that inhabit the Stonebrunt Mountains. Should you be heading in that direction there are some [samples] that I am interested in acquiring.


**You say:** `sample`




>**Akbaq Salid says:** The titan spirits of the Stonebrunt Mountains appear in several various animal forms seemingly with different areas of influence in the spirit world. I am interested in conducting some experiments on the hides of the giant leopard titan and the giant sabretooth titan. Once I have acquired those hides I will seek to conduct experiments on the [others].


**You say:** `other`




>**Akbaq Salid says:** Once I have finished my studies of the feline titans pelts I am interested in experimenting with the hides of the strongest of the stonebrunt titans, the gigantic gorilla and the gargantuan panda. The [ancient snake] that inhabits those mountains is another matter that you may be interested in as well.


**You say:** `ancient snake`




>**Akbaq Salid says:** I believe I have uncovered a process with which to harness the mystical properties of the scales of the snake titan so that they can be fashioned into a powerful robe. If you bring me the ancient snake skin and some platinum thread I am sure there will be enough material to craft multiple robes and I shall reward you with one for your assistance.


else


**You say:** `hail`




>**Akbaq Salid says:** I do not know you well enough to entrust you with such a quest, yet.

end

## Turn-Ins





if ( **Faction is** >= Indifferent) then 


if( **You turn in:** [Giant Leopard Hide](/item/6960), [Giant White Sabertooth Hide](/item/6946)) then 



>**Akbaq Salid says:** These are the pelts of the most powerful of the known Titan spirits. You have done well, Soandso, and you will be rewarded for your services.



* __Faction:__ [Crimson Hands](/faction/233) (5)



* __Faction:__ [High Council of Erudin](/faction/266) (1)



* __Faction:__ [Heretics](/faction/265) (-1)



* __Faction:__ [High Guard of Erudin](/faction/267) (1)



 **You receive:**  [Astral Cloak of the Titans](/item/2573) (+500 exp)


elseif( **You turn in:** [Gigantic Gorilla Hide](/item/6958), [Gargantuan Panda Pelt](/item/6964)) then 



>**Akbaq Salid says:** Excellent! These pelts are in fine condition. I was unsure what would happen to the physical forms of the titans when slain in this realm.
  



* __Faction:__ [Crimson Hands](/faction/233) (5)



* __Faction:__ [High Council of Erudin](/faction/266) (1)



* __Faction:__ [Heretics](/faction/265) (-1)



* __Faction:__ [High Guard of Erudin](/faction/267) (1)



 **You receive:**  [Astral Leggings of the Titans](/item/2575) (+500 exp)


elseif( **You turn in:** [Ancient Snake Skin](/item/6947), [Platinum Thread](/item/12097)) then 



>**Akbaq Salid says:** Ah! I have been anxiously awaiting the oppurtunity to craft some powerful robes from these mystical scales.



* __Faction:__ [Crimson Hands](/faction/233) (5)



* __Faction:__ [High Council of Erudin](/faction/266) (1)



* __Faction:__ [Heretics](/faction/265) (-1)



* __Faction:__ [High Guard of Erudin](/faction/267) (1)



 **You receive:**  [Scaled Robe of the Elder Serpent](/item/2574) (+500 exp)


**This NPC *should* return incorrect items given.**
; 

