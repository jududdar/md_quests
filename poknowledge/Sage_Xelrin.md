# Sage Xelrin
local continue;

## On NPC Spawn

continue = 0;
## Dialog

**You say:** `Hail`



>**Sage Xelrin says:** Greetings Soandso.  I assume you are here to ask about my research?  I imagine that word has spread of my groundbreaking approach to spell creation.  Well I am always willing to enlighten those that choose to learn.  As not to bog you down with too many details. my theory is simple. [Continue]

**You say:** `continue`



continue = 1;


**Set a timer** named *cont* for 60 seconds


>**Sage Xelrin says:** Well the idea is rather basic.  As I am sure you know. there are many magical artifacts in the world with effects that we have not mastered.  It is my conjecture that some of the magic may be extracted from these items in order to further our magical repertoire.  Even in the case where an object has a spell that we already have access to. I believe the binding used to tie the magic to the object could be useful as well. [Continue]

**You say:** `continue`



continue = 0;


>**Sage Xelrin says:** By using this box created in cooperation with the [other sages] in Knowledge. you will be able to either extract a magical scroll or the binding used to hold the magic to the object.  Those elements will be the basis for my research.  Just bring anything you manage to extract for me.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/17176" data-url="17176" class="tooltip-link link">Sage's Box of Research</a>

**You say:** `other sages`



>**Sage Xelrin says:** chuckles. 'Well my associates are working on their own theories for the creation of new magic.  I am sure that their projects are no where near advanced as mine. but even their primitive research could prove a boon in my own work.  If you happen to come across any of their research feel free to show it to my assistants. they will know the best manner in which to process it.  Bring reseach from Balic to Bolcen. and Gunyth's research to Acomar.  Thank you for your assistance.'
end

## Timer(s)

if(e.timer == "cont") then


**Stop timer** named *cont*


continue = 0;
end

## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1027.png" alt="" /> <a
                                href="/item/15952" data-url="15952" class="tooltip-link link">Evocation Binding</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_947.png" alt="" /> <a
                                href="/item/32025" data-url="32025" class="tooltip-link link">Orb of Arcane Visions</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1027.png" alt="" /> <a
                                href="/item/15954" data-url="15954" class="tooltip-link link">Abjuration Binding</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_864.png" alt="" /> <a
                                href="/item/32027" data-url="32027" class="tooltip-link link">Flawed Spell Creation</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15946" data-url="15946" class="tooltip-link link">Word of Combine</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15947" data-url="15947" class="tooltip-link link">Word of Sorcery</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15948" data-url="15948" class="tooltip-link link">Word of Helix</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15949" data-url="15949" class="tooltip-link link">Word of Inverse</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15950" data-url="15950" class="tooltip-link link">Word of Impetus</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15956" data-url="15956" class="tooltip-link link">Aqi Note</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15942" data-url="15942" class="tooltip-link link">Bep Note</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15943" data-url="15943" class="tooltip-link link">Cjo Note</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15944" data-url="15944" class="tooltip-link link">Da Note</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15945" data-url="15945" class="tooltip-link link">Eio Note</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

**This NPC *should* return incorrect items given.**
