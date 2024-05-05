# Charlotte Diggs



[Charlotte Diggs](/npc/19106) is a level 35 Halfling Shopkeeper that spawns in [Rivervale](/zone/19).



## On NPC Spawn

**Set a timer** named *pick_up* for 100 seconds


## Timer(s)

if ( e.timer == "pick_up" and e.self:CheckGround() ) then


>*Charlotte Diggs picks up something from the ground.*


eq.set_timer("pick_up", math.random(3, 150)*1000);
end
