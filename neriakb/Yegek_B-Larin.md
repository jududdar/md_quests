# Yegek B-Larin
## Dialog

**You say:** `hail`



>**Yegek B-Larin says:** Welcome. A brother of the Indigo you must be. Why else would one dare to roam the corridors of the Cauldron of Hate? You were most likely sent to speak with Yegek. If so. speak up and tell Yegek who [sent] you.

**You say:** `seloxia`



if **Faction** >= Amiable then



>**Yegek B-Larin says:** You are a new blood!  I shall help you to face the dangers. For now, you must listen. First we must be sure to increase your skill by combat. Take this bag to the outside and fill it with three beetle eyes and three bone shards from the undead. Combine and return it. Then we shall reward you and continue. Do not lose the short sword you had upon entering our brotherhood. We just may need it later on.



**You receive:**  [Empty Bag](/item/17942)


elseif **Faction** >= Indifferent then



>**Yegek B-Larin says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Yegek B-Larin says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




**You say:** `second test`



if **Faction** >= Amiable then



>**Yegek B-Larin says:** You will now learn what happens to those undesirables who once called themselves Indigo. But first, you will hand me your sword which was given to you by the Indigo Brotherhood. This battle must be fought without a blade. Show us your strength!


elseif **Faction** >= Indifferent then



>**Yegek B-Larin says:** Go! Return when you have done more to serve the Indigo Brotherhood of Neriak. Fewer Leatherfoot Raiders in Nektulos and a few Leatherfoot skullcaps in the palms of Master Narex shall prove your true warrior nature and loyalty to our house.


else



>**Yegek B-Larin says:** Your head will make a fine trophy in the halls of the Indigo Brotherhood.




## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** [Bag of Eyes n Bones](/item/13887)


>**Yegek B-Larin says:** Very nice work. Here are some provisions. Now are you [ready for the second test]?


* __Faction:__ [Indigo Brotherhood](/faction/270) (5)


* __Faction:__ [Emerald Warriors](/faction/326) (-1)


* __Faction:__ [Steel Warriors](/faction/311) (-1)


* __Faction:__ [Primordial Malice](/faction/1522) (-10)


 **You receive:** eq.ChooseRandom( [Iron Ration](/item/13005), [Ration](/item/13007)) (+3000 exp)

elseif **You turn in:** [Short Sword*](/item/9998)


>**Yegek B-Larin says:** Those young warriors who dared to run from battle are now our fodder. They shall help us teach you that sometimes you must kill your own kind. In the center of the arena we have set a coward. Show me you can kill your own when required and bring me his head. Do not grant him mercy nor allow him to flee.


**Spawn NPC:**  [TeirDal coward](/npc/41119) at (**y:** -25, **x:** -1218)

elseif **Faction** >= Amiable and  **You turn in:** [Teir\`Dal Head](/item/13888)


>**Yegek B-Larin says:** You have performed greatly. A coward deserves no pity or mercy. You will be fine addition to our house. Let us replace your weapon with this, a sullied two handed sword! The weapon of a young brother of this hall. It is a finer weapon than your first. Go and spread the hate of Innoruuk.


* __Faction:__ [Indigo Brotherhood](/faction/270) (15)


* __Faction:__ [Emerald Warriors](/faction/326) (-2)


* __Faction:__ [Steel Warriors](/faction/311) (-1)


* __Faction:__ [Primordial Malice](/faction/1522) (-30)


 **You receive:**  [Sullied Two Handed Sword](/item/10830) (+500 exp)


**This NPC *should* return incorrect items given.**






