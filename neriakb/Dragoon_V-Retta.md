# Dragoon V-Retta
## Signals

if(e.signal == 1) then


eq.stop();


eq.move_to(-639,-85,-24,16,true);

elseif(e.signal == 2) then


eq.start(35);
end

## Dialog

**You say:** `hail`



>**Dragoon V-Retta says:** Join us in celebrating my promotion to the rank of Dragoon!  I shall still respect all of you scum.


e.self:DoAnim(67); 
end

## Arrive at Waypoint Script

if(e.wp == 6) then


eq.get_entity_list():GetDoorsByDoorID(1):ForceOpen(e.self);


eq.get_entity_list():GetDoorsByDoorID(2):ForceOpen(e.self);


eq.get_entity_list():GetDoorsByDoorID(49):ForceOpen(e.self);
end