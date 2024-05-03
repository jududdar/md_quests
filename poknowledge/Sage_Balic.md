# Sage Balic






local continue;



## On NPC Spawn

continue = 0;


## Dialog

**You say:** `hail`



>**Sage Balic says:** Greetings friend. Welcome to my place of private contemplation. I relax here and leaf through my old studies, admiring at creations from the past made by races we thought would never amount to anything. My favorite tomes to look at are those that deal with Frogloks.

**You say:** `your research`



>**Sage Balic says:** My research? Oh, I imagine Tenada sent you to me. I'd love to tell you about my studies, if you have time to listen. [Continue]

**You say:** `continue`



continue = 1;


**Set a timer** named *cont* for 60 seconds


>**Sage Balic says:** I have come to Knowledge to fine-tune my abilities in spell craft. To date I've been able to create some minor incantations, but have had little success in creating any magic that was truly revolutionary. I am actually in a bit of a race with the other Sages who are my contemporaries. They too are looking to make a major breakthrough . . . Come to think of it, I could probably find quite a few [uses for their research], should you manage to come by any of it. [Continue]

**You say:** `continue`



continue = 0;


>**Sage Balic says:** Sorry, I digress. Where was I? Oh yes! In the past I, as well as the other Sages, have had little success; however from the volumes of information found here, each of us found a new outlook on the creation of magic. I found that most of the magical discoveries came from existing magical components, mostly runes and words of power. Should you come by any of these components please use this box to check to see if they have the proper magical configuration. The extractor will be able to remove what it needs if you find a valid combination. Right now I believe the box will only function with a single word and rune of approximately the same power.


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_836.png" alt="" /> <a
                                href="/item/17176" data-url="17176" class="tooltip-link link">Sage's Box of Research</a>

**You say:** `their research`



>**Sage Balic says:** Well it couldn't hurt, now could it? If you manage to 'acquire' any of their research feel free to show it to my assistants; Xelrin's research to Tenada and Gunyth's research to Winon downstairs.

**You say:** `froglok`



>**Sage Balic says:** A surprising race to study is the Frogloks of Antonica. While we may think their magic was weak, it was at one time so powerful the Gods reached down and smote them for their creations. Balls of energy that made life into magic! Their High Enchanter even made a mask that transformed the wearer into a Teir\`Dal! Quite an interesting race worthy of some study if you ask me, someday I shall like to go and see these frogloks, especially to learn more knowledge of the magical mask.

**You say:** `magical mask`



>*Sage Balic blinks and looks at you. 'I have told you all that I know, for more knowledge you will need to seek its creator.  The enchanter is more than likely very old, the mask having been made at the height of the power of the Froglok race.  Here take this picture book to aid you in your quest.'  Sage Balic hands you a book.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/11275" data-url="11275" class="tooltip-link link">Picturebook</a>
end



## Timer(s)

if(e.timer == "cont") then


**Stop timer** named *cont*


continue = 0;
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15946" data-url="15946" class="tooltip-link link">Word of Combine</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1121.png" alt="" /> <a
                                href="/item/32019" data-url="32019" class="tooltip-link link">Sage's Apprentice Cap</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15947" data-url="15947" class="tooltip-link link">Word of Sorcery</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/32020" data-url="32020" class="tooltip-link link">Twisted Talisman</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15948" data-url="15948" class="tooltip-link link">Word of Helix</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_616.png" alt="" /> <a
                                href="/item/32021" data-url="32021" class="tooltip-link link">Three Ringed Hoop</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15949" data-url="15949" class="tooltip-link link">Word of Inverse</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_675.png" alt="" /> <a
                                href="/item/32022" data-url="32022" class="tooltip-link link">Joined Signet</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_644.png" alt="" /> <a
                                href="/item/15950" data-url="15950" class="tooltip-link link">Word of Impetus</a>) then 


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_865.png" alt="" /> <a
                                href="/item/32023" data-url="32023" class="tooltip-link link">Apprentice's Notebook</a> (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1027.png" alt="" /> <a
                                href="/item/15952" data-url="15952" class="tooltip-link link">Evocation Binding</a>) then 


 &#127873; **You receive:** 0 (+100000 exp)

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1027.png" alt="" /> <a
                                href="/item/15954" data-url="15954" class="tooltip-link link">Abjuration Binding</a>) then 


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
