# Grahan Rothkar
## Dialog

**You say:** `hail`



>**Grahan Rothkar says:** Hail, Soandso! What business do you have in the pens of the Qeynos Arena? Have you a report of the [escaped catman]?

**You say:** `escaped catman`



>**Grahan Rothkar says:** We had a catman imprisoned here for use in future gladiator battles. He escaped. In the process, he bit off my assistant's hand which held the key to pen number seven. I now seek to hire a warrior to [retrieve key seven].

**You say:** `retrieve key seven`



if( **Faction is** >= Amiable) then 



**You say:** `retrieve key seven`





>**Grahan Rothkar says:** Hmmm. You seem a bit young, but I shall give you a chance. Seek out the catman named Nomala. He most likely returned to [Kerra Isle]. He is not very powerful, but his people are surely watching over him. Retrieve the key for me and be rewarded.



**You say:** `second escaped gladiator`





>**Grahan Rothkar says:** It appears our prize gladiator has escaped. He is a minotaur hero!! Trained by our best. He took down five of our greatest warriors during his escape. Rumor has it he fled to his homeland in the Steamfont Mountains. They say he is an outcast and does not live with his people. He appears during times of great need to champion the minotaurs. Return his shackles to me and glory is yours!!











elseif( **Faction is** == Indifferent) then



>**Grahan Rothkar says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Grahan Rothkar says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!




**You say:** `kerra isle`



>**Grahan Rothkar says:** Kerra Isle is a dangerous place. The Kerra are not a friendly race. There is an island between Erudin and Qeynos which is inhabited by a more docile tribe of Kerra. I hear they took some of their Kerra beetles along with them to the island, too.
end

## Turn-Ins




if( **Faction is** >= Amiable and  **You turn in:** [Pen Key \# 7](/item/20031)


>**Grahan Rothkar says:** I thank you. I must admit I had my doubts, but you have proven yourself a true warrior. I salute you. You can be of some assistance to me.It see ms as though there has been a [second escaped gladiator] and I have a reward waiting for a human warrior.





* __Faction:__ [Steel Warriors](/faction/311) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Knights of Truth](/faction/281) (2)


 **You receive:** None 

elseif( **Faction is** >= Amiable and  **You turn in:** [Minotaur Hero Shackles](/item/12188)


>**Grahan Rothkar says:** You are a true Steel Warrior!! Now you shall wear my hero bracers. I designed them for my greatest gladiators and you have shown yourself mighty enough to wear them.





* __Faction:__ [Steel Warriors](/faction/311) (75)


* __Faction:__ [Guards of Qeynos](/faction/262) (15)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-11)


* __Faction:__ [The Freeport Militia](/faction/330) (-11)


* __Faction:__ [Knights of Truth](/faction/281) (15)


 **You receive:**  [Hero Bracers](/item/12189) (+0 exp)

elseif **You turn in:** [Arena Lion Skin](/item/13398)


>**Grahan Rothkar says:** I salute you. You have done well and crossed into the brotherhood of the Steel Warriors. Welcome. Take this. It is the mark of a Steel Warrior. Live the way of the warrior.





* __Faction:__ [Steel Warriors](/faction/311) (25)


* __Faction:__ [Guards of Qeynos](/faction/262) (5)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-3)


* __Faction:__ [The Freeport Militia](/faction/330) (-3)


* __Faction:__ [Knights of Truth](/faction/281) (5)


 **You receive:**  [Steel Warrior Bracer](/item/13229) (+0 exp)

elseif **You turn in:** [A Sealed Letter](/item/18894)


>**Grahan Rothkar says:** So you are ready to encounter your final test. I wish you well, young warrior. Take this key to the pen on the left along the wall with three doors. There you shall meet your final challenge. Return with proof of victory. Exit before it is at anand I shall not help you.


**Spawn NPC:**  [a young lion](/npc/1005) at (**y:** -120, **x:** -520)


**Set a timer** named *86* for 120 seconds





* __Faction:__ [Steel Warriors](/faction/311) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Knights of Truth](/faction/281) (1)


 **You receive:**  [Pen Key \# 5](/item/20029) (+0 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

if(e.timer == "86") then


**Signaled to:**  [a young lion](/npc/1005)


**Stop timer** named *86*
end


