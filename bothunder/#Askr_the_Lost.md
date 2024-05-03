# Askr the Lost


## Dialog

**You say:** `hail`



>**Askr the Lost says:** Well done.  I did not believe you could have progressed so far, so quickly.  Evynd was one of Agnarr's greatest lieutenants; your victory could not have been easy.  I fear, however, that your task will only become more difficult from here.  With Evynd dead, I can now help you to ascend to the next level.  When you are ready, simply ask and I will [transport] you to the [next level of Torden], but make haste, I cannot stay here for long.




**You say:** `transport`





e.other:CastToClient():MovePC(209, -880, -1787, 1729, 192*2);


if ( e.other:GetPet().valid and not e.other:GetPet():Charmed() ) then



e.other:GetPet():GMMove(-880, -1787, 1729, 0);

end



## On NPC Spawn

**Set a timer** named *depop* for 3300 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**Askr the Lost despawns.**
end
