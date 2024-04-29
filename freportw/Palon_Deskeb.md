# Palon Deskeb
## Dialog

**You say:** `hail`



e.self:Say(string.format("Pleased to meet you. %s. Have you seen how clear the water is underneath the Academy? All sorts of life could flourish there. What a shame there are no [Marr Minnows] there.",e.other:GetName()));

**You say:** `marr minnow`



>**Palon Deskeb says:** The Marr Minnow swims in the pond near the Temple of Marr. I wish I had one. Not a dead one. A live one. I need someone to [get the minnow].

**You say:** `get the minnow`



if **Faction** >= Amiable then



>**Palon Deskeb says:** Please try. Here you are. Take this jar. Offer the jar to the minnows. Maybe they will swim into it.



**You receive:**  [A Jar of Liquid](/item/13861)


elseif **Faction** >= Indifferent then



>**Palon Deskeb says:** The word of mouth in the Academy of Arcane Science is that you are no foe, but you have yet to prove your worth to us. Perform more tasks for the great Tara Neklene.


else



>**Palon Deskeb says:** You had best leave my sight. I am a faithful member of the Academy of Arcane Science and you are no ally of ours.

end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Fish in a Jar](/item/13862)) then


>**Palon Deskeb says:** Oh! A beautiful Marr Minnow. This shall look grand in my aquarium! How lucky that you are a friend to the Academy of Arcane Science. Take your reward.


* __Faction:__ [Arcane Scientists](/faction/220) (5)


* __Faction:__ [Knights of Truth](/faction/281) (1)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


 **You receive:** eq.ChooseRandom( [Torch](/item/13002), [Ration](/item/13007)) (+100 exp)

**This NPC *should* return incorrect items given.**


