# Sir Edwin Motte


## Dialog



**You say:** `hail`



>**Sir Edwin Motte says:** Greetings, Soandso! How lucky you are to encounter the greatness of the legendary Sir Edwin Motte, slayer of cyclopes, battler of beasts, crusher of creatures, masher of monsters, eradicator of evil and champion of the third annual dart championship of Freeport.
end



## On NPC Spawn

**Set a timer** named *timecheck* for 60 seconds


## Timer(s)

if ( e.timer == "timecheck" and not e.self:IsEngaged() ) then




local zoneTime = eq.get_zone_time()["zone_hour"];



if ( zoneTime < 19 and zoneTime > 6 ) then



**Sir Edwin Motte despawns.**

end



## On NPC Death

**Spawn NPC from spawn group:** [Cytodl Krish](/npc/336269) after 1200 second(s)