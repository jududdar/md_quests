# The Protector of Dresolik
## On NPC Death

**Spawn NPC:**  [a flaming cauldron](/npc/212414) at (**y:** 1449, **x:** 166)


**Spawn NPC:**  [a warder of Dresolik](/npc/212419) at (**y:** 1918, **x:** 976)


**Spawn NPC:**  [a warder of Dresolik](/npc/212419) at (**y:** 1982, **x:** 1007)

**Spawn NPC:**  [a warder of Dresolik](/npc/212419) at (**y:** 1918, **x:** 1041)
## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds
## Timer(s)


if ( e.timer == "bounds" ) then




if ( e.self:GetX() > 978 or e.self:GetX() < 558 ) then






e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**The Protector of Dresolik** clears hate list.



**The Protector of Dresolik casts:** [Annul Self](/spell/2830) on themselves.








elseif ( e.timer == "depop" ) then


**The Protector of Dresolik despawns.**
end

## Combat

if  The Protector of Dresolik enters combat  then


eq.pause_timer("depop");


**Set a timer** named *bounds* for 6 seconds

else


eq.resume_timer("depop");


**Stop timer** named *bounds*
end
