# Reiker Rikes



[Reiker Rikes](/npc/174055) is a level 44 Gnome Cleric that spawns in [The Dawnshroud Peaks](/zone/174).






## Dialog

**You say:** `hail`



>**Reiker Rikes says:** I be Reiker Rikes! The fastest gnome in the woods!
end



## Turn-Ins



local mushroom =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1206.png" alt="" /> <a
                                href="/item/31479" data-url="31479" class="tooltip-link link">Fungus Covered Mushroom</a>}



if(mushroom > 0) then


repeat



>*Reiker Rikes grins. 'These should go nicely in my stew.'*



 &#127873; **You receive:** 0 (+15000 exp)

 



mushroom = mushroom - 1;


until mushroom == 0



**This NPC *should* return incorrect items given.**
