# Sirran the Lunatic
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

if **You turn in:** [Miniature Sword](/item/20920)




if(eq.get_qglobals()[sirranName] == "1") then



>**Sirran the Lunatic says:** These are the keys! Use them well! Hold them in your hand and touch them to the runed platforms! Guide you thy will! Hah! The last to go, must tell me so, or be in for a [hassle]! If there's a hassle, I will go!



 **You receive:**  [Key of Swords](/item/20911) 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Miniature Sword](/item/20920) 


elseif **You turn in:** [Lost rabbits foot](/item/20921)



if(eq.get_qglobals()[sirranName] == "1") then



>**Sirran the Lunatic says:** These are the keys! Use them well! Hold them in your hand and touch them to the runed platforms! Guide you thy will! Hah! The last to go, must tell me so, or be in for a [hassle]! If there's a hassle, I will go!



 **You receive:**  [Key of the Misplaced](/item/20912) 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Lost rabbits foot](/item/20921) 


elseif **You turn in:** [Broken Mirror](/item/20922)



if(eq.get_qglobals()[sirranName] == "2") then



>**Sirran the Lunatic says:** You move fast, you crazy kids! Keep going! Prod you I will! Stuck here I have been! Oh! Let me know when you are [done] or this will be no fun! Haha



 **You receive:**  [Key of Misfortune](/item/20913) 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Broken Mirror](/item/20922) 


elseif **You turn in:** [Animal Figurine](/item/20923)



if(eq.get_qglobals()[sirranName] == "3") then



>**Sirran the Lunatic says:** Always want something for nothing? Oh yes, you gave me something! Here you go! Take this! Used one you have. [Teleport] away you will! Let me know, or no kill! Haha!



 **You receive:**  [Key of Beasts](/item/20914) 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Animal Figurine](/item/20923) 


elseif **You turn in:** [Bird Whistle](/item/20924)



if(eq.get_qglobals()[sirranName] == "4") then



>**Sirran the Lunatic says:** What is this? Bah! Take that! And this! What was I thinking? I was thinking you had best let me know when you use those teleporters. Just say, [Icky Bicky Barket]. Aye, that is what I was thinking.



 **You receive:**  [Avian Key](/item/20915) 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Bird Whistle](/item/20924) 


elseif **You turn in:** [Noise Maker](/item/20925)



if(eq.get_qglobals()[sirranName] == "5") then



>**Sirran the Lunatic says:** Phew! These are heavy. Well, not really. I'm sure I don't have to remind you to remind me when you are [leaving].



 **You receive:**  [Key of the Swarm](/item/20916) 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Noise Maker](/item/20925) 


elseif **You turn in:** [Dull Dragon Scale](/item/20926)



if(eq.get_qglobals()[sirranName] == "6") then



>**Sirran the Lunatic says:** Dnib a ni era uoy ro esarhp eht yas dna yrruh!! Sruoy era syek eht dna romra em evig. Erom on gnits seixib eht ahahahahah!



 **You receive:**  [Key of Scale](/item/20917) 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Dull Dragon Scale](/item/20926) 


elseif **You turn in:** [Replica of the Wyrm Queen](/item/20927)



if(eq.get_qglobals()[sirranName] == "7") then



>**Sirran the Lunatic says:** Not too much farther. I spit on thee knave! Ehem. Take these. Go on! Make your fortunes. No one cares about Narris. I mean Sirran. Hah! See if I care what you think! Oh, when did you say you were [leaving]?



 **You receive:**  [Veeshan's Key](/item/20918) 


else



>**Sirran the Lunatic says:** I have no need for this item Soandso, you can have it back.



 **You receive:**  [Replica of the Wyrm Queen](/item/20927) 


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




