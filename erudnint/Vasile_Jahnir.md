# Vasile Jahnir



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


if **Faction** >= Amiable and  **You turn in:** [Summoned: Black Bread](/item/13078), [Summoned: Black Bread](/item/13078), [Summoned: Dagger](/item/7305), [Summoned: Dagger](/item/7305)) then 


>**Vasile Jahnir says:** You have mastered these spells quickly. You shall now wear the gloves of the Gatecaller. Cumbersome they may feel, but they protect the hands of a young magician. In your young days of magic they will protect you from harm. They are not valued much by merchants, but they are prized by other circles. Nevertheless, we offer them only to our young Gatecallers. You may now be of assistance with a [slight problem].





* __Faction:__ [Gate Callers](/faction/254) (5)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [High Guard of Erudin](/faction/267) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:**  [Gloves of the Gatecaller](/item/12209) (+175 exp)


elseif **Faction** >= Amiable and  **You turn in:** [Troll Head](/item/13895)) then 


>**Vasile Jahnir says:** So the rumor shows true. Good work. You are an excellent student and a noble Erudite. Here is your spell as I promised. Go forth and fill your brain with knowledge.





* __Faction:__ [Gate Callers](/faction/254) (10)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [High Guard of Erudin](/faction/267) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:**  [Spell: Fire Flux](/item/15313) (+250 exp)

**This NPC *should* return incorrect items given.**
;

