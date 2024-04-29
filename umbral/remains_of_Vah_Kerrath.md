# remains of Vah Kerrath
## Dialog

**You say:** `hail`



>**remains of Vah Kerrath says:** Fleshy mortal, can you not see that I am cursed to live in eternal anguish? What is it that you seek from me?

**You say:** `vex thal`



if **Faction** >= Warmly +250 then



**You say:** `vex thal`





>**remains of Vah Kerrath says:** The city of shadow is sealed by powerful magic. Only one that wears the talisman of Akelha Ra can pass through the seals on the gate. I have not been beyond the gates but rumors of dark prophets that possess great power have been heard throughout the ages.



**You say:** `dark prophet`





>**remains of Vah Kerrath says:** Only legends and rumors have circulated about the dark prophets in Vex Thal. I suspect that they are the reason for my eternally cursed state. If you could find someway to defeat the dark prophet leading those in Vex Thal and bring me back proof of the deed, I shall reward you with an ancient relic that I possess.




elseif **Faction** >= Indifferent then



>**remains of Vah Kerrath says:** I will not reveal the secrets I have discovered so easily. Since I am unable to leave the protection of the whisperling circle, I will need you to aid me in releasing the Elysian spirits from their tormented states. Destroy their remains and release their spirits from the grip of the shadow curse. Return four of their skulls to me as proof of your deeds. Only then will I impart my discoveries to you.


else



>**remains of Vah Kerrath says:** Begone from my sight corruptor of spirits. I will only aid my allies.

end

## Turn-Ins





if( **You turn in:** [Soul Essence of Aten Ha Ra](/item/8365)) then 


>**remains of Vah Kerrath says:** Soandso, you have done more than was ever expected. Take this and my blessing will be with you always.


 **You receive:**  [Talisman of Vah Kerrath](/item/8364) (+2000 exp)

elseif( **You turn in:** [Elysian Skull](/item/28102), [Elysian Skull](/item/28102), [Elysian Skull](/item/28102), [Elysian Skull](/item/28102)) then


>**remains of Vah Kerrath says:** You have done well. Clear your mind of all distractions and ask the whisperlings if you are worthy of my knowledge.


* __Faction:__ [Whisperling](/faction/1520) (5)


* __Faction:__ [Akheva](/faction/1521) (-1)


 **You receive:** 0 (+1000 exp)

**This NPC *should* return incorrect items given.**
