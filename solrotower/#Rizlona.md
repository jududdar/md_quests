# Rizlona



[Rizlona](/npc/212407) is a level 70 Dragon Warrior that spawns in [Tower of Solusek Ro](/zone/212).



## On NPC Death

**Spawn NPC:**  [a flaming cauldron](/npc/212413) at (**y:** 2717, **x:** -980)


**Spawn NPC:**  [a warder of Rizlona](/npc/212418) at (**y:** 2022, **x:** -1087)


**Spawn NPC:**  [a warder of Rizlona](/npc/212418) at (**y:** 2022, **x:** -1118)

**Spawn NPC:**  [a warder of Rizlona](/npc/212418) at (**y:** 1975, **x:** -1102)


## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds


## Timer(s)


if ( e.timer == "bounds" ) then




if ( e.self:GetY() < 2047 or e.self:GetY() > 2538 ) then






e.self:GMMove(-1103, 2384, -905, 128);



e.self:SetGuardSpot(-1103, 2384, -905, 128);



**Rizlona** clears hate list.



**Rizlona casts:** [Annul Self](/spell/2830) on themselves.





elseif ( e.timer == "depop" ) then


**Rizlona despawns.**
end



## Combat

if  Rizlona enters combat  then


eq.pause_timer("depop");


**Set a timer** named *bounds* for 6 seconds

else


eq.resume_timer("depop");


**Stop timer** named *bounds*
end
