# a shambling cube



[a shambling cube](/npc/114151) is a level 47 Gelatinous Cube Warrior that spawns in [Skyshrine](/zone/114).



## Dialog

**You say:** `hail`



>*a shambling cube emits a low hum.*
end



## On NPC Death

if(e.self:GetLevel() < 43) then


**Spawn NPC:**  [a miniature shambling cube](/npc/114001) at this location.


**Spawn NPC:**  [a miniature shambling cube](/npc/114001) at this location.

else


**Spawn NPC:**  [a small shambling cube](/npc/114000) at this location.


**Spawn NPC:**  [a small shambling cube](/npc/114000) at this location.
end
