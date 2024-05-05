# Vasile Jahnir



[Vasile Jahnir](/npc/23074) is a level 61 Erudite GM Magician that spawns in [Erudin Palace](/zone/23).






## Dialog

**You say:** `hail`



>**Vasile Jahnir says:** Greetings!  You seek knowledge of our ways. You shall find knowledge and you shall offer knowledge you have been taught.  What is the power of the Gatecallers?

**You say:** `slight problem`



if **Faction** >= Amiable then 



**You say:** `slight problem`





>**Vasile Jahnir says:** We have heard rumor of an troll who has taken residence within the forest of Toxxulia. During your travels in Toxxulia, we command you to keep a watchful eye out for the beast. Slay it on sight and return its head to me. To do so will earn you the spell Fire Flux or Burn, whichever may be available at the time.



**You say:** `summoning`





>**Vasile Jahnir says:** Yes. We are the true summoners of Norrath. We are the power supreme. You will learn more and we shall test you. You will go forth and learn the art of summoning. Let your first test be to master the summoning of the dagger and of food. Return to me two summoned daggers and two of the food source you learn to call forth. Do so, and I shall give you the gloves of the Gatecaller.





elseif **Faction** >= Indifferent then



>**Vasile Jahnir says:** A foe of the Gatecallers you are not, but you must do more to earn our respect and trust.


else



>**Vasile Jahnir says:** You dare to approach any of the Gatecallers! You have summoned forth my rage! Leave at once!




end



## Turn-Ins



local text = "Your proof lies in TWO summoned daggers and two summoned loaves of black bread.";


if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_996.png" alt="" /> <a
                                href="/item/13895" data-url="13895" class="tooltip-link link">Troll Head</a>) then 


>**Vasile Jahnir says:** So the rumor shows true. Good work. You are an excellent student and a noble Erudite. Here is your spell as I promised. Go forth and fill your brain with knowledge.





Your faction standing with [Gate Callers](/faction/254) got better (<span class='text-success'>+10</span>)


Your faction standing with [High Council of Erudin](/faction/266) got better (<span class='text-success'>+1</span>)


Your faction standing with [High Guard of Erudin](/faction/267) got better (<span class='text-success'>+1</span>)


Your faction standing with [Heretics](/faction/265) got worse (<span class='text-danger'>-1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/15313" data-url="15313" class="tooltip-link link">Spell: Fire Flux</a> (+250 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-20 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
;

