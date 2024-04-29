# Reiker Rikes



## Dialog

**You say:** `hail`



>**Reiker Rikes says:** I be Reiker Rikes! The fastest gnome in the woods!
end

## Turn-Ins



local mushroom =  **You turn in:**  { [Fungus Covered Mushroom](/item/31479)}



if(mushroom > 0) then


repeat



>*Reiker Rikes grins. 'These should go nicely in my stew.'*



 **You receive:** 0 (+15000 exp)



mushroom = mushroom - 1;


until mushroom == 0



**This NPC *should* return incorrect items given.**
