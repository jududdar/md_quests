# Merko Quetalis



[Merko Quetalis](/npc/8044) is a level 61 Human GM Paladin that spawns in [North Freeport](/zone/8).



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



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18896" data-url="18896" class="tooltip-link link">A note</a>


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




if **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_819.png" alt="" /> <a
                                href="/item/14018" data-url="14018" class="tooltip-link link">A Spider Venom Sac</a>) then 


>**Merko Quetalis says:** You have earned the token of bravery. Now you must ask yourself if you are ready to face true fear. You will have but one chance. If you feel you are powerful enough to easily slay that desert tarantula, then hand me both tokens earned and you shall face the Test of Truth.


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+10</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+2</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/12144" data-url="12144" class="tooltip-link link">Token of Bravery</a> (+100 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/12144" data-url="12144" class="tooltip-link link">Token of Bravery</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/13865" data-url="13865" class="tooltip-link link">Token of Generosity</a>) then 


>**Merko Quetalis says:** Go to the open sewer across the way. Inside you shall find your opponent. Victory shall bring your final token. Return it to me. Remember our ways and remember our foes. Send them to their judgement in the afterlife. Be swift with your thoughts. May Marr be with you.


**Spawn NPC:**  [Guard Willia](/npc/8110) at (**y:** 132, **x:** -257)


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+10</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-1</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+2</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:** 0 (+100 exp)

 

elseif **Faction** >= Amiable and  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_645.png" alt="" /> <a
                                href="/item/13866" data-url="13866" class="tooltip-link link">Token of Truth</a>) then 


>**Merko Quetalis says:** You have performed well. You have shown your allegiance to truth and cast aside the Freeport Militia. The militia will surely despise you from now on. This is how they treat the Knights of Truth. Beware. The followers of Marr stand alone in this city.


Your faction standing with [Knights of Truth](/faction/281) got better (<span class='text-success'>+100</span>)


Your faction standing with [Dismal Rage](/faction/271) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [The Freeport Militia](/faction/330) got worse (<span class='text-danger'>-15</span>)


Your faction standing with [Priests of Marr](/faction/362) got better (<span class='text-success'>+20</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+10</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18828" data-url="18828" class="tooltip-link link">Testimony</a> (+100 exp)

**You receive coin:** 0 <img src='/static/icons/item_644.png' width='14' height='14'/> 1-10 <img src='/static/icons/item_645.png' width='14' height='14'/> 0 <img src='/static/icons/item_646.png' width='14' height='14'/> 0 <img src='/static/icons/item_647.png' width='14' height='14'/> 

**This NPC *should* return incorrect items given.**
