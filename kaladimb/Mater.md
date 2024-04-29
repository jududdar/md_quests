# Mater
## Dialog

**You say:** `hail`



if **Faction** >= Dubious +200 then



>**Mater says:** Welcome to the mines of Kaladim!


else



>**Mater says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `ready to earn mining pick 628`



if **Faction** >= Amiable +100 then 



>**Mater says:** So you have heard of Mining Pick 628 and feel you are ready to wield one? You shall earn one with the return of the ogre head of [Boog Mudtoe] and the 300 gold pieces he still owes me. Don't return unless you have the head and the 300 gold!!


elseif **Faction** >= Indifferent then



>**Mater says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Mater says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.


**You say:** `boog mudtoe`



if **Faction** >= Amiable +100 then 



>**Mater says:** Boog Mudtoe is one of the last remaining ogres of the Mudtoe clan. We helped him escape the assault of the Stormguard for a small fee. Unfortunately for him, we have come to believe his head to be more valuable than the fee. We hear there is someone near the port of Butcherblock who knows of the Mudtoe's whereabouts.


elseif **Faction** >= Indifferent then



>**Mater says:** Don't take this personally, but I can't quite trust you with such matters. Maybe a few less Butcherblock bandits would prove your worth.


else



>**Mater says:** The word around the mines is that you are not to be trusted. You'd best leave before my dagger finds a new home in your back.

end

## Turn-Ins



local text = "I will not hand you a Mining Pick 628 until I see Boog Mudtoe's ogre head and my 300 gold pieces!";



if **Faction** >= Amiable +100 and  **You turn in:** [Ogre Head](/item/13316), gold = 300) then 


>**Mater says:** Very good!! You found him. His head shall bring us a great reward from the Stormguard. And as for you, here is your Mining Pick 628. Only a member of 628 can wield this fine weapon. We are the only ones who can wield it in such a way as to pierce our foes.


* __Faction:__ [Miners Guild 628](/faction/322) (10)



* __Faction:__ [Circle of Unseen Hands](/faction/223) (-10)



* __Faction:__ [Butcherblock Bandits](/faction/379) (-10)



* __Faction:__ [Deeppockets](/faction/241) (10)



* __Faction:__ [Ebon Mask](/faction/244) (-10)



 **You receive:**  [Mining Pick 628](/item/12161) (+5000 exp)


elseif( **You turn in:** [Small, Folded Note](/item/18767)) then 


>**Mater says:** Ah, welcome! We could use some fresh blood around here. The name's Mater, and I run this little outfit. Work hard for me, and I will reward you well. Cross me, and you'll find yourself buried under the mine cap. Now, let's get to work.


* __Faction:__ [Miners Guild 628](/faction/322) (100)




* __Faction:__ [Circle of Unseen Hands](/faction/223) (-5)




* __Faction:__ [Butcherblock Bandits](/faction/379) (-5)




* __Faction:__ [Deeppockets](/faction/241) (5)




* __Faction:__ [Ebon Mask](/faction/244) (-15)




 **You receive:**  [Ruined Miners Tunic*](/item/13516) (+20 exp)



**This NPC *should* return incorrect items given.**

## Timer(s)

>**Mater says:** Blast all these pesky rats!! Jeet, you need to get one of the new rogues.. I mean miners, to get rid of them!!

**Signaled to:**  [Jeet](/npc/67018)