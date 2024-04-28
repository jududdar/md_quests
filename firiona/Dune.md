# Dune
## On NPC Spawn

**Set a timer** named *follow* for 1 seconds
## Timer(s)

if(e.timer == "follow") then


local getmobbynpctype = eq.get_entity_list():GetMobByNpcTypeID(84131);


local follow_target = getmobbynpctype:GetID();


eq.follow(follow_target);


**Stop timer** named *follow*
end

## Turn-Ins



**This NPC *should* return incorrect items given.**





