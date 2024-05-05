# Gornolin



[Gornolin](/npc/4003) is a level 20 Human Shopkeeper that spawns in [Highpass Hold](/zone/5).




## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Gornolin picks an item up from the ground and says, 'Hey! Look what I found! Another piece of rubbish for my trailer... Must be my lucky day.*




## Dialog

**You say:** `hail`



>**Gornolin says:** 'Greetings, my fellow traveler. I am Gornolin Zot, traveling merchant of fine wares. Please. Take a look at what I have to offer.
end
