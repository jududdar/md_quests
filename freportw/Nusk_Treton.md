# Nusk Treton
## Dialog

local fac = e.other:GetFaction(e.self);



**You say:** `hail`



>**Nusk Treton says:** Freeport!!  Great trade city of Norrath!!  What a wondrous place!  How do you do?  You are an [arcane scientist]. are you not?

elseif(fac < 5) then


**You say:** `arcane scientist`




>**Nusk Treton says:** Grand!! I remember my younger days within this great academy. I have spent many years of research here in Freeport. I compiled a [locked journal] of my research. Alas, I am still awaiting its return.


**You say:** `locked journal`




>**Nusk Treton says:** I lent it to an old colleague of mine in Ak'Anon. He was to send it back aboard a private vessel. One Lenka Stoutheart was to return it to me. It has already been one month and counting. I wish there was a young wizard who could [seek out Lenka].


**You say:** `seek out Lenka`




>**Nusk Treton says:** What luck!! I would be most appreciative if you could find Lenka Stoutheart in Freeport and inquire where the journal strongbox might be. I do so look forward to its return.


elseif(fac == 5) then


**You say:** `arcane scientist`




>**Nusk Treton says:** The word of mouth in the Academy of Arcane Science is that you are no foe, but you have yet to prove your worth to us.  Perform a tasks for the great Tara Neklene.


elseif(fac > 5) then


**You say:** `arcane scientist`




>**Nusk Treton says:** You had best leave my sight.  I am a faithful member of the Academy of Arcane Science and you are no ally of ours.

end

## Turn-Ins




if( **Faction is** > Indifferent and  **You turn in:** [A Strongbox](/item/13860)


>**Nusk Treton says:** Grand and fantastic!! You have made my day complete. Here is what little I can offer. Most of my money goes into my research. Thank you.


* __Faction:__ [Arcane Scientists](/faction/220) (10)


* __Faction:__ [Knights of Truth](/faction/281) (2)


* __Faction:__ [Opal Darkbriar](/faction/296) (-1)


* __Faction:__ [The Freeport Militia](/faction/330) (-1)


 **You receive:** None 

**This NPC *should* return incorrect items given.**


