# Bishop Toluwon



[Bishop Toluwon](/npc/200228) is a level 70 Lepertoloth Cleric that spawns in [The Crypt of Decay](/zone/200).

local KNIGHT_SPAWNID = 369225;
local MAGUS_SPAWNID = 369226;



## On NPC Spawn

**Set a timer** named *depop* for 11700 seconds

eq.get_entity_list():GetSpawnByID(KNIGHT_SPAWNID):Enable();

eq.get_entity_list():GetSpawnByID(MAGUS_SPAWNID):Enable();


## Timer(s)

**Bishop Toluwon despawns.**


## Combat

if  Bishop Toluwon enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## On NPC Death

**Zone Wide Emote:** <span class="text-warning">*A raspy voice is heard as the High Priest begins to speak, 'You have come far to seek your demise. Raex! Vindor! My generals to me. Slay these infidels in the name of our lord the Plaguebringer.'*</span>



eq.get_entity_list():GetSpawnByID(KNIGHT_SPAWNID):Disable(false);

eq.get_entity_list():GetSpawnByID(MAGUS_SPAWNID):Disable(false);


**Spawn NPC:**  [\#High Priest Ultor Szanvon](/npc/200245) at (**y:** 318, **x:** 306)

**Spawn NPC:**  [\#Vindor Mawnil](/npc/200261) at (**y:** 294, **x:** 200)

**Spawn NPC:**  [\#Raex Pwodill](/npc/200258) at (**y:** 241, **x:** 496)