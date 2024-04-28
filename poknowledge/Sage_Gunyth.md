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


**You receive:**  [Sage's Box of Research](/item/17176)

**You say:** `task`



>**Sage Gunyth says:** There are two other sages who like to call themselves my equals. They are taking different paths in their studies, and it would be to our benefit to have access to their work, I created that extractor with their aid so I know their methods cannot be far from my own. You must also gather what information you can from their research and return Balic's research to Onirelin Gali my assistant, and Xelrin's research to Xasri Virek his associate. I have nothing more for you, and I have been distracted long enough, be off!
end

## Timer(s)

if(e.timer == "cont") then


**Stop timer** named *cont*


continue = 0;
end

## Turn-Ins





if **You turn in:** [Aqi Note](/item/15956)


 **You receive:** None 

elseif **You turn in:** [Bep Note](/item/15942)


 **You receive:** None 

elseif **You turn in:** [Cjo Note](/item/15943)


 **You receive:** None 

elseif **You turn in:** [Da Note](/item/15944)


 **You receive:** None 

elseif **You turn in:** [Eio Note](/item/15945)


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

elseif **You turn in:** [Word of Combine](/item/15946)


 **You receive:** None 

elseif **You turn in:** [Word of Sorcery](/item/15947)


 **You receive:** None 

elseif **You turn in:** [Word of Helix](/item/15948)


 **You receive:** None 

elseif **You turn in:** [Word of Inverse](/item/15949)


 **You receive:** None 

elseif **You turn in:** [Word of Impetus](/item/15950)


 **You receive:** None 

**This NPC *should* return incorrect items given.**

end