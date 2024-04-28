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


**You receive:**  [Sage's Box of Research](/item/17176)

**You say:** `other sages`



>**Sage Xelrin says:** chuckles. 'Well my associates are working on their own theories for the creation of new magic.  I am sure that their projects are no where near advanced as mine. but even their primitive research could prove a boon in my own work.  If you happen to come across any of their research feel free to show it to my assistants. they will know the best manner in which to process it.  Bring reseach from Balic to Bolcen. and Gunyth's research to Acomar.  Thank you for your assistance.'
end

## Timer(s)

if(e.timer == "cont") then


**Stop timer** named *cont*


continue = 0;
end

## Turn-Ins





if **You turn in:** [Evocation Binding](/item/15952)


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
