# Avhi Escron
local REAVER_LOCS = {

{ 413, 115 },

{ 387, 129 },

{ 388, 153 },

{ 420, 151 },
};

function SpawnReavers(mob, noEmote)

for i, coords in ipairs(REAVER_LOCS) do


eq.spawn2(200259, 0, 0, coords[1], coords[2], -60, 128); 

if ( not noEmote ) then


eq.get_entity_list():MessageClose(mob, true, 200, 0, "Maniacal laughter echoes around the room as the ancient dark lich uses the freshly dead body to summon forth even more reanimated reavers.");
end

function event_hate_list(e)

if ( not e.joined and e.self:GetHP() > 0 ) then


SpawnReavers(e.self);
end



## On NPC Spawn

**Set a timer** named *depop* for 11700 seconds

SpawnReavers(e.self, true);


## Timer(s)

**Avhi Escron despawns.**


## Combat

if  Avhi Escron enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## On NPC Death

**Zone Wide Emote:** <span class="text-warning">*The menacing voice is heard once again saying, 'Betrayer and desecrator of storms I call upon you tothe lives of these fools.*</span>

**Spawn NPC:**  [\#Bishop Toluwon](/npc/200228) at (**y:** 84, **x:** 258)