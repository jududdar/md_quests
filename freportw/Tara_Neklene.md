# Tara Neklene
## Dialog

**You say:** `hail`



>**Tara Neklene says:** It is always a pleasure to meet a new face. We have many who travel far and wide to visit our great academy. Many who brave the long trip by boat. Many who dare to cross the territory of the [Deathfist orcs].

**You say:** `deathfist orcs`



>**Tara Neklene says:** The Deathfist are a clan of orcs. They are not very powerful, yet I hear they dabble in the circles of magic. Their skills in the ways of magic are limited. It is my duty to study them. I shall pay for your services. Will you [assist with the research]?

**You say:** `assist with the research`



>**Tara Neklene says:** Yes. You will do. Go into the lands which surround Freeport. There you shall encounter Deathfist apprentices. They are as young as yourself and each should carry an orc cantrip. Return one for further studies. Do so and you will earn your pay as well as our respect.

**You say:** `test the might of the orc oracles`



if **Faction** >= Amiable +100 then



>**Tara Neklene says:** You have heightened your knowledge to the appropriate rank. You are ready to challenge the Deathfist oracles. Do so and return one oracle scroll which any of them may have. If I am in a good mood when you return, you shall soon be summoning elementals.


elseif **Faction** >= Indifferent then



>**Tara Neklene says:** The word of mouth in the Academy of Arcane Science is that you are no foe, but you have yet to prove your worth to us. Perform more tasks for the great Tara Neklene.


else



>**Tara Neklene says:** You had best leave my sight. I am a faithful member of the Academy of Arcane Science and you are no ally of ours.

end

## Turn-Ins




if **You turn in:** [Illegible Cantrip](/item/13845)


>**Tara Neklene says:** Very fine work, my young apprentice. This shall be very useful in understanding their ways. I have heard rumors of a scribe who can decipher these scrolls. He is said to frequent the local taverns. Bah!! If I cannot decipher them, no one can!! Continue with your work. Soon you shall advance enough to [test the might of the orc oracles].


* __Faction:__ [Arcane Scientists](/faction/220) (10)


* __Faction:__ [Knights of Truth](/faction/281) (2)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


 **You receive:** None 

elseif **Faction** >= Amiable +100 and  **You turn in:** [Illegible Scroll](/item/13225)


>**Tara Neklene says:** Wonderful! You have survived the might of an oracle. With this we can now continue our experiments. Now you may continue your teaching and study the power to summon those of earth, air, water and fire.


* __Faction:__ [Arcane Scientists](/faction/220) (15)


* __Faction:__ [Knights of Truth](/faction/281) (3)


* __Faction:__ [Opal Darkbriar](/faction/296) (-2)


* __Faction:__ [The Freeport Militia](/faction/330) (-2)


 **You receive:** None 

**This NPC *should* return incorrect items given.**

