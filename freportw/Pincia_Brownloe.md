# Pincia Brownloe



[Pincia Brownloe](/npc/9088) is a level 45 Human Shopkeeper that spawns in [West Freeport](/zone/9).



## Dialog

**You say:** `hail`



>**Pincia Brownloe says:** Welcome to Brownloe Bakery. Please try our muffins. One taste and you will yearn for no other. Nothing compares to a Brownloe Muffin!
end



## Turn-Ins



**This NPC *should* return incorrect items given.**



## Signals

if(e.signal == 1) then


>**Pincia Brownloe says:** You are in luck! I have a fresh batch that just came out of the oven!


**Signaled to:**  [Pandos Flintside](/npc/9057)

elseif(e.signal == 2) then


>**Pincia Brownloe says:** Farewell, then. I will make sure to have them ready for you tomorrow!


**Signaled to:**  [Pandos Flintside](/npc/9057)
end

