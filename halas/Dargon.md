# Dargon



[Dargon](/npc/29000) is a level 45 Barbarian Shopkeeper that spawns in [Halas](/zone/29).



## Dialog

**You say:** `Hail`



>**Dargon says:** Hello there, Soandso.  Can I interest you in any components to help you in your research?
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_701.png" alt="" /> <a
                                href="/item/14331" data-url="14331" class="tooltip-link link">Ro's Breath</a>) then 


>**Dargon says:** So, I've been discovered! You must know Camin - he is one of the only people who could have recognized my work. I have worked very hard to mask my presence here.


**Spawn NPC:**  [Arantir Karondor](/npc/29089) at this location.


**Dargon despawns.**



elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1064.png" alt="" /> <a
                                href="/item/14335" data-url="14335" class="tooltip-link link">Arantir's Ring</a>) then


>**Dargon says:** Ah, but it pains my heart to see this. How I could love a women like that is beyond me. And yet, I still do love her. It was on the day I was to ask her to marry me that I lost my powers. When I was about to cast my greatest spell to prove my love to her, my magic failed. She ran out on me that day. But enough of me, do you wish to hear my story?


**Spawn NPC:**  [Arantir Karondor](/npc/29089) at this location.


eq.set_global("wizepicA","1",1,"F");


**Dargon despawns.**



elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_504.png" alt="" /> <a
                                href="/item/18168" data-url="18168" class="tooltip-link link">Note to Arantir</a>) then


**Spawn NPC:**  [Arantir Karondor](/npc/29089) at this location.


eq.set_global("wizepicB","1",1,"F");


eq.delete_global("wizepicA");


**Dargon despawns.**

**This NPC *should* return incorrect items given.**





