# Shintl Lowbrew
## Dialog

**You say:** `hail`



>**Shintl Lowbrew says:** Hail. mighty one! What are you doing in the city?  You should be out slaying beasts. There is nothing to find here in the city.

**You say:** `hollish`



>**Shintl Lowbrew says:** I have never heard of this Hollish character you speak of. You must be confusing me for someone else.

**You say:** `opal`



>**Shintl Lowbrew says:** Opal is just a friend I have here in Freeport. She works at the Academy of Arcane Science.
end

## Arrive at Waypoint Script

if(e.wp == 1) then


eq.create_ground_object(12147,-448,-107,-10.870,0,90000);

elseif(e.wp == 7) then


>**Shintl Lowbrew says:** Any mail for room number two?


**Signaled to:**  [Swin Blackeye](/npc/9103)
end

## On NPC Death

eq.unqiue_spawn(9144,86,0,704,-554,-24,0); 
end