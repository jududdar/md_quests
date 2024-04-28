# Spiritist Roleko


## Dialog

**You say:** `hail`



>**Spiritist Roleko says:** Greetings Traveler. If it is rest you seek then I'm sure you may rest safely within the walls of this outpost. As the sentries keep watch for physical danger I commune with the spirits of this territory to watch for less noticeable threats.
end

## Turn-Ins



local text1 = "I require both the crate of tortured vah shir skulls and the report from Roshawna."

local text2 = "I require the head of the possessed grimling and the skulls of the reanimated grimlings"

local text3 = "In order to perform the ritual I require the Amulet of Golden Rays, Black Flame Charcoal, Thought Leech Brain, and Materialization Ritual"



if **You turn in:** [Resealed Warded Iron Bound Chest](/item/31840), [Roshawna's Report of Occurrences](/item/31841)


>**Spiritist Roleko says:** It was wise of Roshawna to send you to me instead of risk bringing something so tainted by the dark spirits within the walls of Shar Vahl. I shall begin the ritual immediately. What is that?! Look! There is a grimling heading this way followed by what appear to be grimling undead. Defend me while I perform the ritual. Give me the head of that grimling and the skulls of those undead!


* __Faction:__ [Dar Khura](/faction/1533) (5)


 **You receive:** 0 (+1000 exp)


**Spawn NPC:**  [a possessed grimling](/npc/167037) at (**y:** -884, **x:** -956)


**Spawn NPC:**  [a reanimated grimling](/npc/167038) at (**y:** -893, **x:** -956)


**Spawn NPC:**  [a reanimated grimling](/npc/167038) at (**y:** -900, **x:** -956)


**Spawn NPC:**  [a reanimated grimling](/npc/167038) at (**y:** -907, **x:** -956)

elseif **You turn in:** [Possessed Grimling's Head](/item/31847), [Reanmiated Grimling Skull](/item/31848), [Reanmiated Grimling Skull](/item/31848), [Reanmiated Grimling Skull](/item/31848)


>**Spiritist Roleko says:** I am grateful for your assistance. I will be able to complete the rest of the ritual without danger now that the spirits in the skulls have been calmed. Please take this report of occurrences to Scribe Cholsa in Shar Vahl.


* __Faction:__ [Dar Khura](/faction/1533) (4)


 **You receive:**  [Rolekos Report of Occurrences](/item/31849) (+1000 exp)

elseif **You turn in:** [Amulet of Golden Rays](/item/10777), [Black Flame Charcoal](/item/10778), [Thought Leech Brain](/item/10779), [Rakshasa Materialization Ritual](/item/10915)


>**Spiritist Roleko says:** I will need to maintain my concentration to keep the Rakshasa from escaping back into the spirit realm. If you kill him while he is materialized he will be slain and his body will remain material. Bring me the head of the Rakshasa when he is slain.


* __Faction:__ [Dar Khura](/faction/1533) (5)


 **You receive:** 0 (+1000 exp)


**Spawn NPC:**  [Rakshasa Karwoaro](/npc/167039) at (**y:** -867, **x:** -967)

elseif **You turn in:** [Head of the Rakshasa](/item/10916)


>**Spiritist Roleko says:** The threat of the Rakshasa appears to be eliminated. You have the gratitude of the Dar Khura for your bravery and assistance. Let us be wary however, the Rakshasa gained his power by allying with dark spirits that may not be indifferent to the Rakshasas death.


* __Faction:__ [Dar Khura](/faction/1533) (20)


 **You receive:**  [Shield of Bane Warding](/item/31837) (+5000 exp)

**This NPC *should* return incorrect items given.**

