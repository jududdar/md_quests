# Arlyxir


## On NPC Death

**Spawn NPC:**  [a flaming cauldron](/npc/212411) at (**y:** 1891, **x:** 1607)


**Spawn NPC:**  [a warder of Arlyxir](/npc/212416) at (**y:** 1165, **x:** 1726)


**Spawn NPC:**  [a warder of Arlyxir](/npc/212416) at (**y:** 1207, **x:** 1713)

**Spawn NPC:**  [a warder of Arlyxir](/npc/212416) at (**y:** 1207, **x:** 1738)


## Combat

if  Arlyxir enters combat  then


**Set a timer** named *bounds* for 6 seconds


**Set a timer** named *heal* for 750 seconds

else


**Stop timer** named *bounds*


**Stop timer** named *heal*
end



## Timer(s)


if ( e.timer == "bounds" ) then




if ( e.self:GetY() < 1230 ) then



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Arlyxir** clears hate list.



**Arlyxir casts:** [Annul Self](/spell/2830) on themselves.





elseif ( e.timer == "heal" ) then


>*Arlyxir is immolated in flames, and is reborn!*


e.self:Heal();


e.self:CastSpell(1281, e.self:GetTarget():GetID()); 
end
