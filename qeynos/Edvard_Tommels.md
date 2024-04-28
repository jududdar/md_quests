# Edvard Tommels
## Dialog

**You say:** `hail`



>**Edvard Tommels says:** Greetings, Soandso. Thank you for stopping by. Had you heard I was looking for any and all information regarding the Tesch Val incursion? Perhaps you have come to help me gather knowledge? I seek the [Tesch Val scrolls]!


e.self:DoAnim(70); 



**You say:** `scrolls`



>**Edvard Tommels says:** Oh good! I can add them to my collection. We are preparing to make books you know. Bring me any of the scrolls you find in the old Splitpaw lair, and I would be happy to reward you handsomely.
end

## Turn-Ins







local scroll = 0;

local Volone =  **You turn in:**  { [Helle Splitpaw-Haut](/item/18504)}

local Voltwo =  **You turn in:**  { [Tanned Split Paw Skin](/item/18505)}

local Volthree =  **You turn in:**  { [Tanned Split Paw Skin](/item/18506)}

local Volfour =  **You turn in:**  { [Tanned Split Paw Skin](/item/18507)}



if(Volone == 1) then


scroll = scroll + 1;


Volone = 0;

if(Voltwo == 1) then


scroll = scroll + 1;


Voltwo = 0;

if(Volthree == 1) then


scroll = scroll + 1;


Volthree = 0;

if(Volfour == 1) then


scroll = scroll + 1;


Volfour = 0;



if(scroll > 0) then


repeat



if(math.random(100) < 50) then




>**Edvard Tommels says:** Why thank you, Soandso. If you do happen to come across any more of these, please bring them to me.





if(math.random(100) < 50 and not **You possess item:**  [Karanas Tear](/item/12076) x 1




 **You receive:** None 





* __Faction:__ [Qeynos Citizens](/faction/121) (2)



 **You receive:** 0 (+18750 exp)



scroll = scroll - 1;


until scroll == 0;


**This NPC *should* return incorrect items given.**
