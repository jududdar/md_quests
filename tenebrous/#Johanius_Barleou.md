# Johanius Barleou



[Johanius Barleou](/npc/172032) is a level 24 Human Rogue that spawns in [The Tenebrous Mountains](/zone/172).



## Dialog

**You say:** `hail`



if( **Faction is** > Apprehensive) then



>**Johanius Barleou says:** Greetings traveler! You seem like a brave individual for having dared the Tenebrous Mountains without a patrol of Validus Custodus to defend you! I am need of some assistance in an [urgent matter]!


else



>**Johanius Barleou says:** You are a brave individual but unfortunately I cannot trust that you will use what I have to offer to its fullest potential against the foes of Katta Castellum. Perhaps when you have established a stronger reputation as a vampyre slayer I will aid you further.


**You say:** `urgent matter`



>**Johanius Barleou says:** My sister and my beloved Lyrra have been captured by the vile blood suckers are being held in the largest of their dark settlements. I can not face that number of blood suckers alone. Are you prepared to slay the wicked undead?

**You say:** `prepared to slay`



>**Johanius Barleou says:** Excellent, I commend you in advance for your courage. Let us make haste lest something awful happen to my loved ones!


eq.start(6);
end
