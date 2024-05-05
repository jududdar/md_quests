# Edvard Tommels



[Edvard Tommels](/npc/1134) is a level 35 Human Druid that spawns in [South Qeynos](/zone/1).



## Dialog

**You say:** `hail`



>**Edvard Tommels says:** Greetings, Soandso. Thank you for stopping by. Had you heard I was looking for any and all information regarding the Tesch Val incursion? Perhaps you have come to help me gather knowledge? I seek the [Tesch Val scrolls]!


e.self:DoAnim(70); 



**You say:** `scrolls`



>**Edvard Tommels says:** Oh good! I can add them to my collection. We are preparing to make books you know. Bring me any of the scrolls you find in the old Splitpaw lair, and I would be happy to reward you handsomely.
end



## Turn-Ins







local scroll = 0;

local Volone =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/18504" data-url="18504" class="tooltip-link link">Helle Splitpaw-Haut</a>}

local Voltwo =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/18505" data-url="18505" class="tooltip-link link">Tanned Split Paw Skin</a>}

local Volthree =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/18506" data-url="18506" class="tooltip-link link">Tanned Split Paw Skin</a>}

local Volfour =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_682.png" alt="" /> <a
                                href="/item/18507" data-url="18507" class="tooltip-link link">Tanned Split Paw Skin</a>}



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





if(math.random(100) < 50 and not **You possess item:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_534.png" alt="" /> <a
                                href="/item/12076" data-url="12076" class="tooltip-link link">Karanas Tear</a> x 1




 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_534.png" alt="" /> <a
                                href="/item/12076" data-url="12076" class="tooltip-link link">Karanas Tear</a> 

 





Your faction standing with [Qeynos Citizens](/faction/121) got better (<span class='text-success'>+2</span>)



 &#127873; **You receive:** 0 (+18750 exp)

**You receive coin:** 0-2 <img src='/static/icons/item_644.png' width='14' height='14'/> 0-8 <img src='/static/icons/item_645.png' width='14' height='14'/> 0-8 <img src='/static/icons/item_646.png' width='14' height='14'/> 0-15 <img src='/static/icons/item_647.png' width='14' height='14'/> 



scroll = scroll - 1;


until scroll == 0;


**This NPC *should* return incorrect items given.**
