# Sirran the Lunatic



[Sirran the Lunatic](/npc/71058) is a level 55 Halfling Warrior that spawns in [Plane of Sky (Instanced)](/zone/1071).



## On NPC Spawn

**Set a timer** named *bye* for 1200 seconds


## Dialog

local qglobals = eq.get_qglobals();

local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();

**You say:** `hail`



if(qglobals[sirranName] == "1") then 





>**Sirran the Lunatic says:** Ehem! What? Oh, hello there! Sirran be my name. Yes? So, come to the Plane of Sky, have you? Killed all my fairies! Hah! So! Do you wish to know how to traverse this plane? Or should I just go away? I know much about this plane. You would do well to listen!


elseif(qglobals[sirranName] == "2") then 




>**Sirran the Lunatic says:** Ah! Come far you have! You are all crazy! I like it! Swords spin no more! Spin, spin. Unlucky they were! I thought them [vain]!


elseif(qglobals[sirranName] == "3") then 




>**Sirran the Lunatic says:** What! Die already! Come so far. Can't you see I am cold! Give me a cloak or something! Bah! You don't look the type to give anything! Be off with you, then!



>**Sirran the Lunatic says:** Always want something for nothing? Oh yes, you gave me something! Here you go! Take this! Used one you have. [Teleport] away you will! Let me know, or no kill! Haha!


elseif(qglobals[sirranName] == "4") then 




>**Sirran the Lunatic says:** What is this? Bah! Take that! And this! What was I thinking? I was thinking you had best let me know when you use those teleporters. Just say, [Icky Bicky Barket]. Aye, that is what I was thinking.


elseif(qglobals[sirranName] == "5") then 




>**Sirran the Lunatic says:** Children, run to the wall and give the deputies some milk. Oh, I almost forgot. Give me your trinkets, or give me death!


elseif(qglobals[sirranName] == "7") then 




>**Sirran the Lunatic says:** Nyah! The tears are welling up in my eyes! I am so proud. I think of you as if I were your father! Sniff. Sniff. Give me Veeshan, and I give you death


**You say:** `citanul eht narris, liah`




>**Sirran the Lunatic says:** Lortap llaw taerg eht fo lahsram, Narris lahsram ma I. Flesym ecudortni ot em wolla. Sgniteerg

**You say:** `llaw eht htiw eno I ma`





>**Sirran the Lunatic says:** Kcul doog! Ouy rof ydaer si erips eht fo retsis eht won, sdik boj doog.


if(**spawned NPC:**  [\#Sister of the Spire](/npc/71076) == false) then



**Spawn NPC:**  [\#Sister of the Spire](/npc/71076) at (**y:** -1035, **x:** -929)









**You say:** `plane`



>**Sirran the Lunatic says:** Ahah! Wise you are and tell you I will. Hrm? Don't have wings, do you? Fairies have swords! Fairies stole my lucky feet! Hand me them, one by one, and be in for a treat! Haha!
end



## Turn-Ins



local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();

if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/20920" data-url="20920" class="tooltip-link link">Miniature Sword</a>) then 




if(eq.get_qglobals()[sirranName] == "1") then



>**Sirran the Lunatic says:** These are the keys! Use them well! Hold them in your hand and touch them to the runed platforms! Guide you thy will! Hah! The last to go, must tell me so, or be in for a [hassle]! If there's a hassle, I will go!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/20911" data-url="20911" class="tooltip-link link">Key of Swords</a> 

 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_591.png" alt="" /> <a
                                href="/item/20920" data-url="20920" class="tooltip-link link">Miniature Sword</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_915.png" alt="" /> <a
                                href="/item/20921" data-url="20921" class="tooltip-link link">Lost rabbits foot</a>) then 



if(eq.get_qglobals()[sirranName] == "1") then



>**Sirran the Lunatic says:** These are the keys! Use them well! Hold them in your hand and touch them to the runed platforms! Guide you thy will! Hah! The last to go, must tell me so, or be in for a [hassle]! If there's a hassle, I will go!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_807.png" alt="" /> <a
                                href="/item/20912" data-url="20912" class="tooltip-link link">Key of the Misplaced</a> 

 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_915.png" alt="" /> <a
                                href="/item/20921" data-url="20921" class="tooltip-link link">Lost rabbits foot</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1129.png" alt="" /> <a
                                href="/item/20922" data-url="20922" class="tooltip-link link">Broken Mirror</a>) then 



if(eq.get_qglobals()[sirranName] == "2") then



>**Sirran the Lunatic says:** You move fast, you crazy kids! Keep going! Prod you I will! Stuck here I have been! Oh! Let me know when you are [done] or this will be no fun! Haha



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_998.png" alt="" /> <a
                                href="/item/20913" data-url="20913" class="tooltip-link link">Key of Misfortune</a> 

 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1129.png" alt="" /> <a
                                href="/item/20922" data-url="20922" class="tooltip-link link">Broken Mirror</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/20923" data-url="20923" class="tooltip-link link">Animal Figurine</a>) then 



if(eq.get_qglobals()[sirranName] == "3") then



>**Sirran the Lunatic says:** Always want something for nothing? Oh yes, you gave me something! Here you go! Take this! Used one you have. [Teleport] away you will! Let me know, or no kill! Haha!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_651.png" alt="" /> <a
                                href="/item/20914" data-url="20914" class="tooltip-link link">Key of Beasts</a> 

 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_895.png" alt="" /> <a
                                href="/item/20923" data-url="20923" class="tooltip-link link">Animal Figurine</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/20924" data-url="20924" class="tooltip-link link">Bird Whistle</a>) then 



if(eq.get_qglobals()[sirranName] == "4") then



>**Sirran the Lunatic says:** What is this? Bah! Take that! And this! What was I thinking? I was thinking you had best let me know when you use those teleporters. Just say, [Icky Bicky Barket]. Aye, that is what I was thinking.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1146.png" alt="" /> <a
                                href="/item/20915" data-url="20915" class="tooltip-link link">Avian Key</a> 

 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_510.png" alt="" /> <a
                                href="/item/20924" data-url="20924" class="tooltip-link link">Bird Whistle</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_551.png" alt="" /> <a
                                href="/item/20925" data-url="20925" class="tooltip-link link">Noise Maker</a>) then 



if(eq.get_qglobals()[sirranName] == "5") then



>**Sirran the Lunatic says:** Phew! These are heavy. Well, not really. I'm sure I don't have to remind you to remind me when you are [leaving].



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_956.png" alt="" /> <a
                                href="/item/20916" data-url="20916" class="tooltip-link link">Key of the Swarm</a> 

 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_551.png" alt="" /> <a
                                href="/item/20925" data-url="20925" class="tooltip-link link">Noise Maker</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1136.png" alt="" /> <a
                                href="/item/20926" data-url="20926" class="tooltip-link link">Dull Dragon Scale</a>) then 



if(eq.get_qglobals()[sirranName] == "6") then



>**Sirran the Lunatic says:** Dnib a ni era uoy ro esarhp eht yas dna yrruh!! Sruoy era syek eht dna romra em evig. Erom on gnits seixib eht ahahahahah!



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_963.png" alt="" /> <a
                                href="/item/20917" data-url="20917" class="tooltip-link link">Key of Scale</a> 

 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1136.png" alt="" /> <a
                                href="/item/20926" data-url="20926" class="tooltip-link link">Dull Dragon Scale</a> 

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_893.png" alt="" /> <a
                                href="/item/20927" data-url="20927" class="tooltip-link link">Replica of the Wyrm Queen</a>) then 



if(eq.get_qglobals()[sirranName] == "7") then



>**Sirran the Lunatic says:** Not too much farther. I spit on thee knave! Ehem. Take these. Go on! Make your fortunes. No one cares about Narris. I mean Sirran. Hah! See if I care what you think! Oh, when did you say you were [leaving]?



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_952.png" alt="" /> <a
                                href="/item/20918" data-url="20918" class="tooltip-link link">Veeshan's Key</a> 

 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_893.png" alt="" /> <a
                                href="/item/20927" data-url="20927" class="tooltip-link link">Replica of the Wyrm Queen</a> 

 


**This NPC *should* return incorrect items given.**



## Combat

if(e.joined == true) then


**Sirran the Lunatic shouts:** <span class="text-danger">What?! Now you've done it! The bunnies are angry! ANGRY I TELL YOU!</span>
end



## Timer(s)

if(e.timer == "bye") then


**Stop timer** named *bye*


**Sirran the Lunatic despawns.**
end



## On NPC Death

local sirranName = "sirran";

sirranName = sirranName .. eq.get_zone_guild_id();

eq.delete_global(sirranName);




