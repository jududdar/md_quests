# Natasha Whitewater


## On NPC Spawn

**Natasha Whitewater shouts:** <span class="text-danger">The Triumvirate of Water has decreed your fate, Shmendrik Lavawalker!! I am here to deliver said fate!!</span>
## Dialog

**You say:** `hail`



>**Natasha Whitewater says:** The Riptide goblins must have their crown returned to them. If you would be so kind as to give me the crown I will make sure that it reaches them. Hopefully they are capable enough to repair the damage that has been done to it.
end

## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_523.png" alt="" /> <a
                                href="/item/28046" data-url="28046" class="tooltip-link link">Damaged Goblin Crown</a>) then 


>**Natasha Whitewater says:** I will have this crown returned to the Riptide Goblins immediately! Should you ever come across an Erudite named Omat Vastsea, give him this sea shell. The waters of Norrath shimmer with awareness of your deeds here today!


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1223.png" alt="" /> <a
                                href="/item/28047" data-url="28047" class="tooltip-link link">Ornate Sea Shell</a> 

 


**Natasha Whitewater despawns.**

**This NPC *should* return incorrect items given.**

## Signals

if(e.signal == 1) then


>**Natasha Whitewater says:** Enough!! Your existence has come to an


**Signaled to:**  [Shmendrik Lavawalker](/npc/51012)

elseif(e.signal == 2) then


>**Natasha Whitewater says:** This conflict has been destined by the waters of the Triumvirate!
end

## Arrive at Waypoint Script

if(e.wp == 4 and **spawned NPC:**  [Shmendrik Lavawalker](/npc/51012)) then


**Signaled to:**  [Shmendrik Lavawalker](/npc/51012)


**Natasha Whitewater attacks NPC:**  [Shmendrik Lavawalker](/npc/51012)
end





