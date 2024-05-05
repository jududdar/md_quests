# Captain Klunga



[Captain Klunga](/npc/70072) is a level 35 Skeleton Warrior that spawns in [Dagnor's Cauldron](/zone/70).



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




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_891.png" alt="" /> <a
                                href="/item/12278" data-url="12278" class="tooltip-link link">Abandoned Orc Shovel</a>) then


**Stop timer** named *depop*


eq.start(2);

**This NPC *should* return incorrect items given.**
;


## Arrive at Waypoint Script

if(e.wp == 1) then


**Spawns on ground:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_688.png" alt="" /> <a
                                href="/item/12274" data-url="12274" class="tooltip-link link">Chalice of Conquest</a> at location.

elseif(e.wp ==2) then


e.self:SetNPCFactionID(79);
end

