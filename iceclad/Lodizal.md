# Lodizal
## Arrive at Waypoint Script

if(e.wp == 1) then


>*Lodizal sniffs and turns slowly, its huge head swinging from side to side as it looks for food.*

elseif(e.wp == 4) then


>*Lodizal roars at the village angrily, its trail of destruction stretching behind.*

elseif(e.wp == 6) then


>*Lodizal bellows one last time, its fiery maw satiated by its angry feeding. It heads towards the ocean, its gut full and its anger quenched.*


if(**spawned NPC:**  [Keref Spiritspear](/npc/110050)) then



eq.get_entity_list():GetMobByNpcTypeID( [Keref Spiritspear](/npc/110050)):Emote("sniffs at the air, its teeth still bared in distrust.  With a growl, it relaxes as it realizes the horrible sea monster has left the village in peace.");



if(**spawned NPC:**  [Grizlin Bloodfang](/npc/110008)) then



eq.get_entity_list():GetMobByNpcTypeID( [Grizlin Bloodfang](/npc/110008)):Emote("sniffs at the air, its teeth still bared in distrust.  With a growl, it relaxes as it realizes the horrible sea monster has left the village in peace.");



if(**spawned NPC:**  [Ergrez Shortpaw](/npc/110010)) then



eq.get_entity_list():GetMobByNpcTypeID( [Ergrez Shortpaw](/npc/110010)):Emote("sniffs at the air, its teeth still bared in distrust.  With a growl, it relaxes as it realizes the horrible sea monster has left the village in peace.");


elseif(e.wp == 7) then


>*Lodizal bellows and thrashes around. His flippers kick hard snow and ice into the air. His maw snaps and opens like a promise of death.*
end
