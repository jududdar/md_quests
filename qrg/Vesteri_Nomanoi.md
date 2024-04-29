# Vesteri Nomanoi
## Dialog

**You say:** `hail`



>**Vesteri Nomanoi says:** Hail, Soandso. I am Vesteri Namanoi. I provide training to the Jaggedpine Treefolk and their allies. If you are not busy, I would like to ask a small [favor] of you.

**You say:** `favor`



if **Faction** >= Amiable then 



>**Vesteri Nomanoi says:** I need you to take this claim check to Qeynos for me. Nesiff Talaherd is a woodcarver who owns a shop in South Qeynos. I am having him carve a small statue of Tunare for Te'Anara. With my training schedule, I can not make the journey to Qeynos. Please give this claim check to Nesiff and bring the statue to me. It is a surprise, so please do not say anything to Te'Anara about it.



**You receive:**  [Claim Check](/item/18012)


elseif **Faction** >= Indifferent then



>**Vesteri Nomanoi says:** We, the Jaggedpine Treefolk, appreciate the help you've given us in the past. But, we must trust you more before allowing you to handle such important matters.




else



>**Vesteri Nomanoi says:** You are an enemy of the Jaggedpine Treefolk, this forest, and the residents of it. Begone, before I am forced to take drastic measures!



end

## Turn-Ins




if **Faction** >= Amiable and  **You turn in:** [Wooden Statue](/item/13864)) then


>**Vesteri Nomanoi says:** Oh thank you so much! Here. Take this reward for your time. I will also tell Te'Anara of you.


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (5)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [QRG Protected Animals](/faction/343) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


* __Faction:__ [Guards of Qeynos](/faction/262) (1)


 **You receive:** 0 (+250 exp)

**This NPC *should* return incorrect items given.**
