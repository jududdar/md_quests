# Xuzl



[Xuzl](/npc/212055) is a level 75 Fiend Warrior that spawns in [Tower of Solusek Ro](/zone/212).



## On NPC Death

**Spawn NPC:**  [a flaming cauldron](/npc/212410) at (**y:** -336, **x:** 1780)


**Spawn NPC:**  [a warder of Xuzl](/npc/212415) at (**y:** -1040, **x:** 1837)


**Spawn NPC:**  [a warder of Xuzl](/npc/212415) at (**y:** -1091, **x:** 1880)

**Spawn NPC:**  [a warder of Xuzl](/npc/212415) at (**y:** -1091, **x:** 1800)


## Combat

if  Xuzl enters combat  then


**Set a timer** named *bounds* for 6 seconds

else


**Stop timer** named *bounds*
end



## Timer(s)


if ( e.timer == "bounds" ) then




if ( e.self:GetY() < -914 ) then



>*Xuzl bellows in a deep voice, 'You shall not distract me from my conjurings!'*



e.self:GMMove(e.self:GetSpawnPointX(), e.self:GetSpawnPointY(), e.self:GetSpawnPointZ(), e.self:GetSpawnPointH());



**Xuzl** clears hate list.



**Xuzl casts:** [Annul Self](/spell/2830) on themselves.

end
