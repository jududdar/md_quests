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



if **Faction** >= Amiable +100 and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_920.png" alt="" /> <a
                                href="/item/13316" data-url="13316" class="tooltip-link link">Ogre Head</a>, gold = 300) then 


>**Mater says:** Very good!! You found him. His head shall bring us a great reward from the Stormguard. And as for you, here is your Mining Pick 628. Only a member of 628 can wield this fine weapon. We are the only ones who can wield it in such a way as to pierce our foes.


Your faction standing with [Miners Guild 628](/faction/322) got better (<span class='text-success'>+10</span>)



Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-10</span>)



Your faction standing with [Butcherblock Bandits](/faction/379) got worse (<span class='text-danger'>-10</span>)



Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+10</span>)



Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-10</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_888.png" alt="" /> <a
                                href="/item/12161" data-url="12161" class="tooltip-link link">Mining Pick 628</a> (+5000 exp)

 


elseif( **You turn in:** item1 =  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18767" data-url="18767" class="tooltip-link link">Small, Folded Note</a>) then 


>**Mater says:** Ah, welcome! We could use some fresh blood around here. The name's Mater, and I run this little outfit. Work hard for me, and I will reward you well. Cross me, and you'll find yourself buried under the mine cap. Now, let's get to work.


Your faction standing with [Miners Guild 628](/faction/322) got better (<span class='text-success'>+100</span>)




Your faction standing with [Circle of Unseen Hands](/faction/223) got worse (<span class='text-danger'>-5</span>)




Your faction standing with [Butcherblock Bandits](/faction/379) got worse (<span class='text-danger'>-5</span>)




Your faction standing with [Deeppockets](/faction/241) got better (<span class='text-success'>+5</span>)




Your faction standing with [Ebon Mask](/faction/244) got worse (<span class='text-danger'>-15</span>)




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_678.png" alt="" /> <a
                                href="/item/13516" data-url="13516" class="tooltip-link link">Ruined Miners Tunic*</a> (+20 exp)

 



**This NPC *should* return incorrect items given.**

## Timer(s)

>**Mater says:** Blast all these pesky rats!! Jeet, you need to get one of the new rogues.. I mean miners, to get rid of them!!

**Signaled to:**  [Jeet](/npc/67018)