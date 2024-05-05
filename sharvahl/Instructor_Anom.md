# Instructor Anom



[Instructor Anom](/npc/155126) is a level 50 Vah Shir Warrior that spawns in [The City of Shar Vahl](/zone/155).

local count;


## On NPC Spawn

count = 0;

**Set a timer** named *train* for 7 seconds


## Timer(s)

count = count + 1;

if(count==3) then


>**Instructor Anom says:** Listen up, recruits! Your lives will depend on your ability to deal with an enemy in unarmed combat.

if(count==4) then


>**Instructor Anom says:** If you are comfortable in unarmed combat, you will be able to understand the worst cast scenario of any given situation.

if(count==5) then


>**Instructor Anom says:** If you are caught by surprise, Your ability to fight with your feet and fists will be the base from which you will have to work.

if(count==6) then


>**Instructor Anom says:** If that foundation is a strong one, you will have little to worry about... even in the most dire of situations.


**Set a timer** named *train* for 25 seconds

if(count==7) then


>**Instructor Anom says:** Are you two ready to spar?


**Signaled to:**  [Recruit Ulra](/npc/155131)


**Set a timer** named *train* for 5 seconds

if(count==8) then


**Signaled to:**  [Recruit Ulra](/npc/155131)


**Set a timer** named *train* for 90 seconds

if(count==9) then


count = 0;


**Set a timer** named *train* for 7 seconds
end



## Signals

if(e.signal == 1) then


>**Instructor Anom says:** Recruit, don't guess... Bring up your guard and fight! 

if(e.signal == 2) then


>**Instructor Anom says:** Good good! Ease up on him, Mogol. Both of you, take a break for a moment.
end



## Turn-Ins



**This NPC *should* return incorrect items given.**





