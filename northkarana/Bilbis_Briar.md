# Bilbis Briar



[Bilbis Briar](/npc/13075) is a level 45 Human Shopkeeper that spawns in [Northern Plains of Karana](/zone/13).




## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Bilbis Briar picks up something from the ground.*


end