# Merko Quetalis
## Dialog

**You say:** `hail`



>**Merko Quetalis says:** Hail, good citizen!  You have entered the Hall of Truth.  What is it you seek?  Many citizens come to request aid in dealing with the local rogues or the oppression of our sworn enemies, the Freeport Militia.  A few valiant ones have been [summoned to the Hall of Truth].

**You say:** `summoned.* hall.* truth`



if **Faction** >= Amiable then




>**Merko Quetalis says:** You have been summoned? You do not have the look of nobility. You must be a [squire]. There are many squires who have been summoned to our Hall. Not all pass the [Test of Truth].


elseif **Faction** >= Indifferent then




>**Merko Quetalis says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Merko Quetalis says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `squire`



if **Faction** >= Amiable then




>**Merko Quetalis says:** Then I welcome you, Squire. Being a squire is the first step to becoming a true knight of the Hall of Truth. Remember always to protect and serve the meek. I have a [small task] which suits a squire perfectly.


elseif **Faction** >= Indifferent then




>**Merko Quetalis says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Merko Quetalis says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `small task`



if **Faction** >= Amiable then




>**Merko Quetalis says:** Venture to the Commonlands and seek out our noble friend Altunic Jartin. He lives and works out of his home. Hand him this note.



**You receive:**  [A note](/item/18896)


elseif **Faction** >= Indifferent then




>**Merko Quetalis says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Merko Quetalis says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `token of generosity`



if **Faction** >= Amiable then




>**Merko Quetalis says:** Go to the deserts of North Ro. Seek out the desert tarantulas. Stand and face this dreaded creature. If you are lucky, you will find a venom sac. This is what I require. When you return, hand it to me.


elseif **Faction** >= Indifferent then




>**Merko Quetalis says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Merko Quetalis says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `test of truth`



if **Faction** >= Amiable then




>**Merko Quetalis says:** Only when a squire is ready, may he tempt his fate. All he need do is hand the tokens of bravery and generosity to me. If the squire survives his ordeal, then he or she shall enter the order of the Knights of Truth. The squire will be given the Testimony of Truth and become a respected knight.


elseif **Faction** >= Indifferent then




>**Merko Quetalis says:** Work on the ways of valor before we discuss such things. You are on the righteous path of the Truthbringer, but there is more work to do.


else



>**Merko Quetalis says:** Leave my presence at once. Your ways of life are not acceptable to one who follows the Truthbringer.


**You say:** `willia`



>**Merko Quetalis says:** She is my niece. Lucan ordered her to kill my wife.. She did. She now belongs to the Freeport Militia. As part of the militia, she must die!! Let no militia member stand in the way of nobility.

**You say:** `heal`



>**Merko Quetalis says:** If you require the binding of wounds you should speak with Palious Jartan in the temple. He will be glad to help you.
end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [A Spider Venom Sac](/item/14018)


>**Merko Quetalis says:** You have earned the token of bravery. Now you must ask yourself if you are ready to face true fear. You will have but one chance. If you feel you are powerful enough to easily slay that desert tarantula, then hand me both tokens earned and you shall face the Test of Truth.


* __Faction:__ [Knights of Truth](/faction/281) (10)


* __Faction:__ [Dismal Rage](/faction/271) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Priests of Marr](/faction/362) (2)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:**  [Token of Bravery](/item/12144) (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Token of Bravery](/item/12144), [Token of Generosity](/item/13865)


>**Merko Quetalis says:** Go to the open sewer across the way. Inside you shall find your opponent. Victory shall bring your final token. Return it to me. Remember our ways and remember our foes. Send them to their judgement in the afterlife. Be swift with your thoughts. May Marr be with you.


**Spawn NPC:**  [Guard Willia](/npc/8110) at (**y:** 132, **x:** -257)


* __Faction:__ [Knights of Truth](/faction/281) (10)


* __Faction:__ [Dismal Rage](/faction/271) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


* __Faction:__ [Priests of Marr](/faction/362) (2)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:** 0 (+100 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Token of Truth](/item/13866)


>**Merko Quetalis says:** You have performed well. You have shown your allegiance to truth and cast aside the Freeport Militia. The militia will surely despise you from now on. This is how they treat the Knights of Truth. Beware. The followers of Marr stand alone in this city.


* __Faction:__ [Knights of Truth](/faction/281) (100)


* __Faction:__ [Dismal Rage](/faction/271) (-15)


* __Faction:__ [The Freeport Militia](/faction/330) (-15)


* __Faction:__ [Priests of Marr](/faction/362) (20)


* __Faction:__ [Steel Warriors](/faction/311) (10)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
