# Lokar To-Biath



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Lokar To-Biath says:** I am the Scribe of Innoruuk. If you do not have business with me, begone!


else



>**Lokar To-Biath says:** Your reputation precedes you. You are no friend to the Dark Bargainers.




**You say:** `scribe of dal`



if **Faction** >= Indifferent then



>**Lokar To-Biath says:** The Scribes of Dal? All of them are long since [dead].. or at least most would say that.


else



>**Lokar To-Biath says:** Your reputation precedes you. You are no friend to the Dark Bargainers.




**You say:** `dead`



if **Faction** >= Indifferent then



>**Lokar To-Biath says:** Perhaps, perhaps not. I cannot remember, but perhaps Innoruuk would help me remember should you tithe him a bottle of red wine from the Blind Fish.


else



>**Lokar To-Biath says:** Your reputation precedes you. You are no friend to the Dark Bargainers.




**You say:** `vow`



if **Faction** >= Indifferent then






>**Lokar To-Biath says:** Break the vow? She might. Were you to tithe 70 gold to your god, Innoruuk, he might aid you.


else



>**Lokar To-Biath says:** Your reputation precedes you. You are no friend to the Dark Bargainers.




**You say:** `innoruuk`



if **Faction** >= Indifferent then



>**Lokar To-Biath says:** I am his scribe, and He is our god.  There is nothing else to be said.


else



>**Lokar To-Biath says:** Your reputation precedes you. You are no friend to the Dark Bargainers.



end

## Turn-Ins





local Red_Wine =  **You turn in:**  { [Red Wine](/item/13030)}



if **Faction** >= Indifferent and  **You turn in:** platinum = 7) then


>**Lokar To-Biath says:** Take this note to the Scribe of Dal, and perhaps she will break her vow.





* __Faction:__ [Dark Bargainers](/faction/236) (10)




* __Faction:__ [Dreadguard Inner](/faction/370) (1)


* __Faction:__ [Dreadguard Outer](/faction/334) (1)


 **You receive:**  [A Note](/item/18200) 

elseif(Red_Wine > 0) then


repeat



>**Lokar To-Biath says:** Ah, yes, let me pray to our god.. Yes, Innoruuk has given me wisdom. A Scribe of Dal still exists, disguised as a barkeep in the Blind Fish. This information will not help you though, for she has sworn a [vow] of silence and will not speak of the Dal.







* __Faction:__ [Dark Bargainers](/faction/236) (10)






* __Faction:__ [Dreadguard Inner](/faction/370) (1)



* __Faction:__ [Dreadguard Outer](/faction/334) (1)



 **You receive:** 0 (+10 exp)



Red_Wine = Red_Wine - 1;


until Red_Wine == 0;

**This NPC *should* return incorrect items given.**

## On NPC Death

>**Lokar To-Biath says:** The death of a Dark Bargainer never goes unnoticed!