# Trankia



[Trankia](/npc/30068) is a level 47 Barbarian Rogue that spawns in [Everfrost Peaks](/zone/30).





## Dialog

**You say:** `hail`



>**Trankia says:** Hmmph.
 
**You say:** `avenge your brother`



>**Trankia says:** My brother was part of a raiding party that adventured into the Caverns of Guk. Somewhere within he was betrayed and left for dead by the dastardly brother of Karg IceBear - Martar. I want you to find me what remains of my brothers body and bring it back to me. I am told that he died within a mine shaft.
end



## Turn-Ins



local text = "Wait, Soandso, are you not forgetting something?";


if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_507.png" alt="" /> <a
                                href="/item/10528" data-url="10528" class="tooltip-link link">Shadowed Ball</a>) then


>**Trankia says:** You must be another one from Vilissia. I will tell you what I tell all the others - you must help me [avenge] my [brother] before I will help you attain Tishan's Kilt.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18797" data-url="18797" class="tooltip-link link">A tattered note</a> (+500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_980.png" alt="" /> <a
                                href="/item/10556" data-url="10556" class="tooltip-link link">A Barbarian Head</a>) then


>**Trankia says:** Oh Wulfthan, look what has become of you. I told you that you should not have trusted Martar.  Soandso, as a final service, I want you to kill Martar IceBear for me. He is known to roam these parts. Bring me the Warthread Kilt that he wears and my two reminder notes, and I will give to you Tishan's Kilt.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18798" data-url="18798" class="tooltip-link link">A tattered note</a> (+500 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_843.png" alt="" /> <a
                                href="/item/1347" data-url="1347" class="tooltip-link link">Warthread Kilt</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18797" data-url="18797" class="tooltip-link link">A tattered note</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18798" data-url="18798" class="tooltip-link link">A tattered note</a>) then


>**Trankia says:** Ah, Wulfthan, you are at last avenged. Thank you, Soandso- please take this kilt as a reward for services well done.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_843.png" alt="" /> <a
                                href="/item/2365" data-url="2365" class="tooltip-link link">Tishan's Kilt</a> (+1500 exp)

 

**This NPC *should* return incorrect items given.**
;
