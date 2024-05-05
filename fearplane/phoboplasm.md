# phoboplasm



[phoboplasm](/npc/72082) is a level 48 Gelatinous Cube Warrior that spawns in [Plane of Fear](/zone/72).



## Signals

if(e.signal == 1) then


>**phoboplasm says:** Such is the will of Cazic-Thule!
end



## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*phoboplasm absorbs a discarded item into its corrosive body.*


end