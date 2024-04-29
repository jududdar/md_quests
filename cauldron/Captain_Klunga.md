# Captain Klunga
## On NPC Spawn

**Set a timer** named *playdead* for 1 seconds
## Timer(s)

if(e.timer == "playdead") then


e.self:SetAppearance(3);


**Stop timer** named *playdead*


**Set a timer** named *depop* for 3600 seconds

elseif(e.timer == "depop") then


**Stop timer** named *depop*


**Captain Klunga despawns.**
end

## Turn-Ins




if( **You turn in:** [Abandoned Orc Shovel](/item/12278)) then


**Stop timer** named *depop*


eq.start(2);

**This NPC *should* return incorrect items given.**
;
## Arrive at Waypoint Script

if(e.wp == 1) then


**Spawns on ground:**  [Chalice of Conquest](/item/12274) at location.

elseif(e.wp ==2) then


e.self:SetNPCFactionID(79);
end

