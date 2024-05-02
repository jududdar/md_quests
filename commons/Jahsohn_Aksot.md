# Jahsohn Aksot
## Dialog

**You say:** `hail`



>**Jahsohn Aksot says:** Greetings, Soandso.

**You say:** `rykas`



>**Jahsohn Aksot says:** I have not heard of anyone speaking that name out loud in years. Rykas once shared a tale with me, though I have lived with fear in my mind ever since. He told me afterwards that I did not have the balance I thought I had. Have you come for the Words of Magi'kot?

**You say:** `words`



>**Jahsohn Aksot says:** The Words of Magi'kot can only be shared with those elementalists whose minds are of balance. The Words were separated into three pieces by a high council of Magi who feared that the story would bring anto elementalists throughout Norrath. If you feel you wish to read from the sacred Power of the Orb then an elementalist of such power should easily accomplish this task.

**You say:** `what task`



>**Jahsohn Aksot says:** Bring me the torn pages of Magi'kot. The first section can be found in the depths of a tainted forest, warded by an angry lupine. It is also rumored that one section is found in the haunted estate of a murderer, on a many armed creature. The last may be found in the belly of an amphibian who thirsts for blood.
end



## Turn-Ins



local text = "Have you forgotten something, Soandso?";




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/28035" data-url="28035" class="tooltip-link link">Token of Mastery</a>) then


>**Jahsohn Aksot says:** What is this? I cannot believe you found it! Where did you get this?


 &#127873; **You receive:** 0 (+50 exp)

 

elseif( **You turn in:** item1 =  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28000" data-url="28000" class="tooltip-link link">Torn Page of Magi\`kot pg. 1</a>,item2 =  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28001" data-url="28001" class="tooltip-link link">Torn Page of Magi\`kot pg. 2</a>,item3 =  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28002" data-url="28002" class="tooltip-link link">Torn Page of Magi\`kot pg. 3</a>) then


>**Jahsohn Aksot says:** Rykas may have been right about you, Soandso. Now, go find Walnan. Walnan was apprenticed to a very powerful Mage. After her apprenticeship was complete, she wished to begin teaching other beings of Norrath. Even those who knew nothing of the art! I do not believe she was successful, though. Seek her out to further your tale. Good luck in your journeys, Soandso!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/28003" data-url="28003" class="tooltip-link link">Words of Magi\`kot</a> 

 

**This NPC *should* return incorrect items given.**



