# Noxhil V-Sek
## Dialog

**You say:** `hail`



>**Noxhil V-Sek says:** Greetings, Soandso!  We of the Dead are proud to have you among us.  Your lineage is well known.  Still, you must learn to claw your way to the upper echelon.  There are many [menial tasks] to be performed before you can truly be inducted as a member.

**You say:** `menial tasks`



>**Noxhil V-Sek says:** You cannot avoid the toil of peons. We have all spent our time in the lower ranks. There are duties such as [collecting beetle eyes].

**You say:** `beetle eye`



if **Faction** >= Amiable then



>**Noxhil V-Sek says:** Take this chest.  It has been fitted with a mold designed to hold ten beetle eyes.  We require them for further experiments.  Do not return until you fill the chest.



**You receive:**  [Empty Box](/item/17930)


elseif **Faction** >= Indifferent then



>**Noxhil V-Sek says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Noxhil V-Sek says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `other components`



if **Faction** >= Amiable then



>**Noxhil V-Sek says:** Take this chest. This one must be filled with [Kerra Isle beetle] eyes. When you finish filling the chest, be sure to return to me with a [wooly mammoth] tusk also. Be quick about it and I just may reward you with something special.



**You receive:**  [Empty Chest](/item/17932)


elseif **Faction** >= Indifferent then



>**Noxhil V-Sek says:** When you learn to serve the Dead, then I will find the time to speak of such things.


else



>**Noxhil V-Sek says:** How dare you enter my presence?!  In the name of the Dead I should strike you down!




**You say:** `kerra isle beetle`



>**Noxhil V-Sek says:** The shipping route between Qeynos and Erudin includes a stop on an island filled with friendly catpeople. Also on this isle is the Kerra Isle beetle. It is indigenous to Kerra Isle and the catpeople are very protective of them.

**You say:** `mammoth`



>**Noxhil V-Sek says:** I hear that wooly mammoths can be found in the peaks of Everfrost. They are fierce beasts. I would hate to annoy one.
end

## Turn-Ins



local randomloot = math.random(1,3);

local text = "I was expecting a mammoth tusk and the combined beetle eye box!";



if **Faction** >= Amiable and  **You turn in:** [Box of Beetle Eyes](/item/13389)


>**Noxhil V-Sek says:** Fantastic work, my child! We shall store these for further experiments. Take this as extra payment for a fine job. You have done so well I believe you can assist in obtaining two [other components].


* __Faction:__ [The Dead](/faction/239) (10)


* __Faction:__ [Queen Cristanos Thex](/faction/303) (1)


* __Faction:__ [King Naythox Thex](/faction/278) (-1)


* __Faction:__ [Keepers of the Art](/faction/275) (-1)


* __Faction:__ [Eldritch Collective](/faction/245) (-1)


* __Faction:__ [Primordial Malice](/faction/1522) (-20)


if(randomloot == 1) then



 **You receive:** None 


elseif(randomloot == 2) then



 **You receive:** None 


elseif(randomloot == 3) then



 **You receive:** None 


elseif **Faction** >= Amiable and  **You turn in:** [Beetle Eye Chest](/item/13395), [Mammoth Tusks](/item/10124)


>**Noxhil V-Sek says:** Excellent work, young one! You are sure to be an asset to our faction. Let us see if we can help you on your journey to power. I believe this can be of assistance to a young necromancer of the Dead.


* __Faction:__ [The Dead](/faction/239) (20)


* __Faction:__ [Queen Cristanos Thex](/faction/303) (3)


* __Faction:__ [King Naythox Thex](/faction/278) (-3)


* __Faction:__ [Keepers of the Art](/faction/275) (-3)


* __Faction:__ [Eldritch Collective](/faction/245) (-3)


* __Faction:__ [Primordial Malice](/faction/1522) (-40)


 **You receive:** eq.ChooseRandom( [Spell: Bind Affinity](/item/15035), [Spell: Convoke Shadow](/item/15362), [Spell: Lifedraw](/item/15445), [Spell: Engulfing Darkness](/item/15355), [Spell: Heat Blood](/item/15360), [Spell: Wave of Enfeeblement](/item/15363)) (+17150 exp)

**This NPC *should* return incorrect items given.**






