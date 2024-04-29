# Natasha Whitewater


## On NPC Spawn

**Natasha Whitewater shouts:** <span class="text-danger">The Triumvirate of Water has decreed your fate, Shmendrik Lavawalker!! I am here to deliver said fate!!</span>
## Dialog

**You say:** `hail`



>**Natasha Whitewater says:** The Riptide goblins must have their crown returned to them. If you would be so kind as to give me the crown I will make sure that it reaches them. Hopefully they are capable enough to repair the damage that has been done to it.
end

## Turn-Ins



if( **You turn in:** [Damaged Goblin Crown](/item/28046)) then 


>**Natasha Whitewater says:** I will have this crown returned to the Riptide Goblins immediately! Should you ever come across an Erudite named Omat Vastsea, give him this sea shell. The waters of Norrath shimmer with awareness of your deeds here today!


 **You receive:**  [Ornate Sea Shell](/item/28047) 


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





