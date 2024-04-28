# Gornolin
## On NPC Spawn

**Set a timer** named *nosell* for 1 seconds

**Set a timer** named *pick_up* for 2 seconds
## Timer(s)

if(e.timer == "nosell") then


**Stop timer** named *nosell*


e.self:MerchantCloseShop();

elseif( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Gornolin picks an item up from the ground and says, 'Hey! Look what I found! Another piece of rubbish for my trailer... Must be my lucky day.*

end

## Dialog

**You say:** `hail`



>**Gornolin says:** Greetings, my fellow traveler. I am Gornolin Zot, traveling merchant of fine wares. Please. Take a look at what I have to offer.
end

## Arrive at Waypoint Script

if(e.wp == 1 or e.wp == 6) then


e.self:SetRunning(true);

elseif(e.wp == 4 or e.wp == 7) then


e.self:SetRunning(false);
end
