# Bizzznawa



[Bizzznawa](/npc/126220) is a level 41 Bixie Warrior that spawns in [Plane of Mischief](/zone/126).



## On NPC Spawn

**Set a timer** named *follow* for 1 seconds


## Timer(s)

if(e.timer == "follow") then


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(126235);





if(mobtypeID) then



local follow_mob = mobtypeID:GetID();



eq.follow(follow_mob,0);



**Stop timer** named *follow*

end
