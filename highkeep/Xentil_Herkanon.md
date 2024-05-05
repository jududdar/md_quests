# Xentil Herkanon



[Xentil Herkanon](/npc/6185) is a level 12 Half Elf Rogue that spawns in [High Keep](/zone/6).



## On NPC Spawn

**Set a timer** named *depop* for 1800 seconds


## Turn-Ins



**This NPC *should* return incorrect items given.**



## On NPC Death

**Signaled to:**  [Lartin](/npc/6186)

**Signaled to:**  [Grex](/npc/6187)

**Stop timer** named *depop*


## Timer(s)

if(e.timer == "depop") then


**Signaled to:**  [Lartin](/npc/6186)


**Signaled to:**  [Grex](/npc/6187)




**Xentil Herkanon despawns.**
end
