# Guard McCluskey



[Guard McCluskey](/npc/12090) is a level 34 Human Warrior that spawns in [Western Plains of Karana](/zone/12).



## On NPC Spawn
  e.self:SetRunning(true);


## Signals

if(e.signal == 1) then


>**Guard McCluskey says:** Time to push our weight around. Ahhh. There is nothing better than being a Qeynos Guard.


eq.start(18)

elseif(e.signal == 2) then


>**Guard McCluskey says:** Ha! You do that and see what happens. No one will miss another untalented, voiceless bard!
end



## Arrive at Waypoint Script

if(e.wp == 1) then


>**Guard McCluskey says:** Hello again, Ms. Storyswapper! Did I ever tell you about the new song tax that was attached to last week's bard tax? You'd best pay up or I will be forced to lock you up in the dungeon.


**Signaled to:**  [Misty Storyswapper](/npc/12100)

elseif(e.wp == 2) then


eq.stop();


eq.move_to(-2026,-2926,44,223,true);
end
