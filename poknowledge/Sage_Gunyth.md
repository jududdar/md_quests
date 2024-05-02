# Sage Gunyth
local continue;

## On NPC Spawn

continue = 0;
## Dialog

**You say:** `Hail`



>**Sage Gunyth says:** turns a condescending eye toward you. 'I am quite busy here. and I do not appreciate interruptions.  My [research] is important. and I do not have time to explain everything to you.'

**You say:** `research`



>**Sage Gunyth says:** Well it seems that I am not going to rid myself of you so easily so I will explain what I can. I will be sure to use small words and simple concepts so you will be sure to understand. Every spell is much like an orchestra; there are different instruments and octaves, and every instrument has a range of notes. These notes are the important component. [continue]

**You say:** `continue`



continue = 1;


**Set a timer** named *cont* for 60 seconds


>**Sage Gunyth says:** It is my theory that all of the notes have been discovered, and creating new spells will just be a matter of combining notes in new and different fashions. Since you seem so interested in my research, I can use assistance in gathering notes. I have separated all teh spells that are readily accessible to me, but I do not have time to gather components from the more difficult to obtain spells. [Continue]

**You say:** `continue`



continue = 0;


>**Sage Gunyth says:** I have constructed this extractor to break spells apart into their notes. It will not work on all spells, and I do not have time to compile a list of spells that it will and will not work on. As my apprentice, as that seems to be what you are intent on becoming, you will separate any spells you come across and return the notes to me where, you will need to insert four spell scrolls of the same power belonging to different arcane circles. For some reason the extractor only works for spells between the 10th and 14th circles, I hope to have that problem resolved soon. This extractor is not simple to use, and you will find you will have more success with the more powerful spells if you have a greater understanding on how spells are constructed. There is one more [task] that I require of my understudy.'


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/17176" data-url="17176" class="tooltip-link link">Sage's Box of Research</a>

**You say:** `task`



>**Sage Gunyth says:** There are two other sages who like to call themselves my equals. They are taking different paths in their studies, and it would be to our benefit to have access to their work, I created that extractor with their aid so I know their methods cannot be far from my own. You must also gather what information you can from their research and return Balic's research to Onirelin Gali my assistant, and Xelrin's research to Xasri Virek his associate. I have nothing more for you, and I have been distracted long enough, be off!
end

## Timer(s)

if(e.timer == "cont") then


**Stop timer** named *cont*


continue = 0;
end

## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15956" data-url="15956" class="tooltip-link link">Aqi Note</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1002.png" alt="" /> <a
                                href="/item/32014" data-url="32014" class="tooltip-link link">Talisman of Research</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15942" data-url="15942" class="tooltip-link link">Bep Note</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1058.png" alt="" /> <a
                                href="/item/32015" data-url="32015" class="tooltip-link link">Amulet of Knowledge</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15943" data-url="15943" class="tooltip-link link">Cjo Note</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1357.png" alt="" /> <a
                                href="/item/32016" data-url="32016" class="tooltip-link link">Book of Forgotten Magic</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15944" data-url="15944" class="tooltip-link link">Da Note</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_755.png" alt="" /> <a
                                href="/item/32017" data-url="32017" class="tooltip-link link">Arcane Quill</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_968.png" alt="" /> <a
                                href="/item/15945" data-url="15945" class="tooltip-link link">Eio Note</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_945.png" alt="" /> <a
                                href="/item/32018" data-url="32018" class="tooltip-link link">Gem of Flowing Breath</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1027.png" alt="" /> <a
                                href="/item/15952" data-url="15952" class="tooltip-link link">Evocation Binding</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1027.png" alt="" /> <a
                                href="/item/15954" data-url="15954" class="tooltip-link link">Abjuration Binding</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

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

 

**This NPC *should* return incorrect items given.**

end