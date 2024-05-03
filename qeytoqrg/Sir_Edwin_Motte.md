# Sir Edwin Motte


## Dialog

**You say:** `hail`



>**Sir Edwin Motte says:** Greetings, Soandso! How lucky you are to encounter the greatness of the legendary Sir Edwin Motte, slayer of cyclopes, battler of beasts, crusher of creatures, masher of monsters, eradicator of evil and champion of the third annual dart championship of Freeport.
end



## Arrive at Waypoint Script

if(e.wp == 1 or e.wp == 6) then


e.self:SetRunning(true);

elseif(e.wp == 4 or e.wp == 7) then


e.self:SetRunning(false);
end
