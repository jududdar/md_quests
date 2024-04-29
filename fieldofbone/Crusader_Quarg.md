# Crusader Quarg



## Dialog

**You say:** `hail`



>*Crusader Quarg stands at attention and salutes you.  It would seem that he takes his job quite seriously.  'Do not fear, feeble soul.  The Crusaders of Greenmist are on duty.*

**You say:** `collect.* rok nilok`



if **Faction** >= Amiable then



>**Crusader Quarg says:** Take this chest.  Inside, you shall combine the skull of their leader and at least five of the caste members.  You must then go to the swamp garrison and deliver the full chest along with your iron cudgel of the mystic to Mystic Dovan.  Go to him now and inquire of the crusaders of Rok Nilok.



**You receive:**  [A Skull Chest](/item/17035)


elseif **Faction** >= Indifferent then



>**Crusader Quarg says:** Show greater devotion to the Crusaders of Greenmist and you will obtain that which you seek.


else



>*Crusader Quarg eye's glare red and gnashes his teeth.  'You had best avoid all members of the Temple of Terror.*

end

## Turn-Ins





if **Faction** >= Amiable and  **You turn in:** [The Bone Garrison](/item/18054)) then


>**Crusader Quarg says:** Ah, i see you have proven yourself to Zand and he wishes to see more of your prowess.  go to the Tower of Kurn and bring him the Skulls of the Caste of Bone Brethren, a caste of powerful shamans who perished fighting undead in the Field of Bone several decades ago.


* __Faction:__ [Scaled Mystics](/faction/445) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (10)


 **You receive:**  [A Skull Chest](/item/17034) (+10000 exp)



elseif **Faction** >= Amiable and  **You turn in:** [Full C.O.B.B. Chest](/item/12735), [Iron Cudgel of the Seer](/item/5142)) then


>**Crusader Quarg says:** The temple shall be pleased. As instructed by the Hierophants, here is your Iron Cudgel of the Mystic. You have done well that I must ask you to [collect the Crusaders of Rok Nilok].


* __Faction:__ [Scaled Mystics](/faction/445) (10)


* __Faction:__ [Legion of Cabilis](/faction/441) (10)


 **You receive:**  [Iron Cudgel of the Mystic](/item/5143) (+20000 exp)

**This NPC *should* return incorrect items given.**
 




