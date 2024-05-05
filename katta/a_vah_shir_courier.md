# a vah shir courier



[a vah shir courier](/npc/160171) is a level 38 Vah Shir Warrior that spawns in [Katta Castellum](/zone/160).



## On NPC Spawn

**Set a timer** named *run* for 1 seconds


## Timer(s)

if(e.timer == "run") then


e.self:SetRunning(true);
end



## Arrive at Waypoint Script

rosh = eq.get_entity_list():GetMobByNpcTypeID(160126);

if(e.wp == 4) then


e.self:SetRunning(false);

elseif(e.wp == 8) then


if(rosh.valid) then



>**a vah shir courier says:** Sorry for the delay mistress, I ran into a spot of trouble on the way here. I am prepared to deliver your crate to the spiritists back home.



rosh:Say("I hope your journey back to Shar Vahl is less eventful. Please make haste, the spiritists must receive this crate as soon as possible.");



>*a vah shir courier tucks the crate of skulls under his arm and nods to Roshawna. Suddenly the courier begins to shake, his fur stands on and his eyes glaze over expressionlessly. The courier runs for the gates of Katta Castellum with an otherworldly howl echoing in his wake.*



e.self:AddItem(17079,1);



rosh:Say("Stop him! Stop the courier! An evil spirit has possessed him! He must not escape with those skulls! Catch him and bring back that crate of skulls!");



e.self:SetRunning(true);

end






## On NPC Death

if(e.self:GetWaypointID() > 8 and e.self:GetWaypointID() <= 14) then


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.

elseif(e.self:GetWaypointID() > 14) then


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.


**Spawn NPC:**  [a reanimated Vah Shir](/npc/160172) at this location.
end


