# a grotesque statue
local entityIDs = {};

## On NPC Spawn

**Set a timer** named *depop* for 60 seconds

**Set a timer** named *lay* for 0 seconds

**Set a timer** named *attack* for 6 seconds



entityIDs[e.self:GetID()] = e.self:GetX();
## Combat

if  a grotesque statue enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end

## Timer(s)

if ( e.timer == "depop" ) then


local id = entityIDs[e.self:GetID()];


if ( id and id == -1954 ) then






eq.get_entity_list():GetSpawnByID(365397):SetTimer(1);


elseif ( id and id == -1748 ) then



eq.get_entity_list():GetSpawnByID(366053):SetTimer(1);


elseif ( id and id == -1736 ) then



eq.get_entity_list():GetSpawnByID(366176):SetTimer(1);


elseif ( id and id == -1958 ) then



eq.get_entity_list():GetSpawnByID(367232):SetTimer(1);



entityIDs[e.self:GetID()] = nil;


**a grotesque statue despawns.**




elseif ( e.timer == "lay" ) then


**Stop timer** named *lay*


e.self:SetAppearance(3);


elseif ( e.timer == "attack" ) then


**Stop timer** named *attack*


e.self:SetAggroRange(500);
end
