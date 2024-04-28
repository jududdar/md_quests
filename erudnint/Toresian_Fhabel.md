# Toresian Fhabel


## Dialog

**You say:** `hail`



>**Toresian Fhabel says:** Welcome. my friend! We are the Craftkeepers. We study the circle of magic called enchantment. What circle do you [study]?

**You say:** `study enchantment`



>**Toresian Fhabel says:** Then I welcome you into our circle. It is good to see new blood.


if(**spawned NPC:**  [Slansin](/npc/23078) == false or **spawned NPC:** 23001 ==  false) then



eq.unique_spawn(eq.ChooseRandom( [Slansin](/npc/23078),23001),0,0,575,683,-12.13,78); 


**You say:** `study wizard`



>**Toresian Fhabel says:** Then you should visit with the Crimson Hands. They are also found within the Palace of Erud.

**You say:** `study magic`



>**Toresian Fhabel says:** The ways of magic are not ours. You should speak with the Gatecallers. They will assist you.


**You say:** `study heretic`



>**Toresian Fhabel says:** What?! Do not jest. Every Erudite knows better than to speak of the forbidden black arts. Do not contemplate studying those arts. You do not want to go the way of the black-hearted heretics.


**You say:** `assist`



if **Faction** >= Amiable then 



>**Toresian Fhabel says:** Ahhhhh Soandso. Slansin used to have need of those potions, however he mysteriously disappeared long ago. The only person I know of who still wants them is a cleric of the Church of Marr in Freeport.



**You receive:**  [Inert Potion](/item/13983)


elseif **Faction** >= Indifferent then




>**Toresian Fhabel says:** You are most welcome to the circle of the Craftkeepers, but I require more service before we can discuss such things.




else



>**Toresian Fhabel says:** You are lucky to be standing. Leave here immediately or suffer grave consequences! You are not welcome amongst the Craftkeepers.

end

## Turn-Ins



**This NPC *should* return incorrect items given.**
;
