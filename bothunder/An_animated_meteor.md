# An animated meteor



[An animated meteor](/npc/209138) is a level 60 Dervish Warrior that spawns in [Bastion of Thunder](/zone/209).



## On NPC Spawn

**Set a timer** named *depop* for 600 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**An animated meteor despawns.**
end



## Combat

if  An animated meteor enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");





if ( e.self:GetZ() > 1800 and e.self:Charmed() ) then


e.self:BuffFadeByEffect(22);


e.self:ModifyNPCStat("mr", "200");
end
