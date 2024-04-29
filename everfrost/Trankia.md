# Trankia


## Dialog

**You say:** `hail`



>**Trankia says:** Hmmph.
 
**You say:** `avenge your brother`



>**Trankia says:** My brother was part of a raiding party that adventured into the Caverns of Guk. Somewhere within he was betrayed and left for dead by the dastardly brother of Karg IceBear - Martar. I want you to find me what remains of my brothers body and bring it back to me. I am told that he died within a mine shaft.
end

## Turn-Ins



local text = "Wait, Soandso, are you not forgetting something?";


if( **You turn in:** [Shadowed Ball](/item/10528)) then


>**Trankia says:** You must be another one from Vilissia. I will tell you what I tell all the others - you must help me [avenge] my [brother] before I will help you attain Tishan's Kilt.


 **You receive:**  [A tattered note](/item/18797) (+500 exp)

elseif( **You turn in:** [A Barbarian Head](/item/10556)) then


>**Trankia says:** Oh Wulfthan, look what has become of you. I told you that you should not have trusted Martar.  Soandso, as a final service, I want you to kill Martar IceBear for me. He is known to roam these parts. Bring me the Warthread Kilt that he wears and my two reminder notes, and I will give to you Tishan's Kilt.


 **You receive:**  [A tattered note](/item/18798) (+500 exp)

elseif( **You turn in:** [Warthread Kilt](/item/1347), [A tattered note](/item/18797), [A tattered note](/item/18798)) then


>**Trankia says:** Ah, Wulfthan, you are at last avenged. Thank you, Soandso- please take this kilt as a reward for services well done.


 **You receive:**  [Tishan's Kilt](/item/2365) (+1500 exp)

**This NPC *should* return incorrect items given.**
;
