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


**You receive:**  [Sage's Box of Research](/item/17176)

**You say:** `their research`



>**Sage Balic says:** Well it couldn't hurt, now could it? If you manage to 'acquire' any of their research feel free to show it to my assistants; Xelrin's research to Tenada and Gunyth's research to Winon downstairs.

**You say:** `froglok`



>**Sage Balic says:** A surprising race to study is the Frogloks of Antonica. While we may think their magic was weak, it was at one time so powerful the Gods reached down and smote them for their creations. Balls of energy that made life into magic! Their High Enchanter even made a mask that transformed the wearer into a Teir\`Dal! Quite an interesting race worthy of some study if you ask me, someday I shall like to go and see these frogloks, especially to learn more knowledge of the magical mask.

**You say:** `magical mask`



>*Sage Balic blinks and looks at you. 'I have told you all that I know, for more knowledge you will need to seek its creator.  The enchanter is more than likely very old, the mask having been made at the height of the power of the Froglok race.  Here take this picture book to aid you in your quest.'  Sage Balic hands you a book.*


**You receive:**  [Picturebook](/item/11275)
end

## Timer(s)

if(e.timer == "cont") then


**Stop timer** named *cont*


continue = 0;
end

## Turn-Ins





if **You turn in:** [Word of Combine](/item/15946)


 **You receive:** None 

elseif **You turn in:** [Word of Sorcery](/item/15947)


 **You receive:** None 

elseif **You turn in:** [Word of Helix](/item/15948)


 **You receive:** None 

elseif **You turn in:** [Word of Inverse](/item/15949)


 **You receive:** None 

elseif **You turn in:** [Word of Impetus](/item/15950)


 **You receive:** None 

elseif **You turn in:** [Evocation Binding](/item/15952)


 **You receive:** None 

elseif **You turn in:** [Abjuration Binding](/item/15954)


 **You receive:** None 

elseif **You turn in:** [Spell: Strong Poison](/item/15955)


 **You receive:** None 

elseif **You turn in:** [Spell: Ykesha](/item/15951)


 **You receive:** None 

elseif **You turn in:** [Spell: Screaming Mace](/item/15953)


 **You receive:** None 

elseif **You turn in:** [Aqi Note](/item/15956)


 **You receive:** None 

elseif **You turn in:** [Bep Note](/item/15942)


 **You receive:** None 

elseif **You turn in:** [Cjo Note](/item/15943)


 **You receive:** None 

elseif **You turn in:** [Da Note](/item/15944)


 **You receive:** None 

elseif **You turn in:** [Eio Note](/item/15945)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
