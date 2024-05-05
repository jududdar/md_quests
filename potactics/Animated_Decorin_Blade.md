# Animated Decorin Blade



[Animated Decorin Blade](/npc/214310) is a level 57 Invisible Man Warrior that spawns in [Drunder, the Fortress of Zek](/zone/214).

local TAGRIN_TYPE = 214054;



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds


## Combat

if  Animated Decorin Blade enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");





local mob = eq.get_entity_list():GetMobByNpcTypeID(TAGRIN_TYPE);


if ( mob and mob.valid and mob:IsEngaged() ) then



local t = mob:GetHateRandomClient();



if ( t and t.valid ) then




e.self:AddToHateList(t);



end



## Timer(s)

if ( e.timer == "depop" ) then


**Animated Decorin Blade despawns.**
end
