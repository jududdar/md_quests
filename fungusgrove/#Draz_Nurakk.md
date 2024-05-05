# Draz Nurakk



[Draz Nurakk](/npc/157009) is a level 55 Iksar Beastlord that spawns in [The Fungus Grove](/zone/157).



## On NPC Spawn

**Set a timer** named *depop* for 3600 seconds


## Timer(s)

if(e.timer == "depop") then


**Stop timer** named *depop*


**Despawn NPC:**  [\#Draz Nurakks Warder](/npc/157069)


**Draz Nurakk despawns.**
end



## Combat

if Draz Nurakk enters combat  then


eq.get_entity_list():GetMobByNpcTypeID( [\#Draz Nurakks Warder](/npc/157069)):AddToHateList(e.other,1);


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end

function event_death(e)

**Signaled to:**  [\#Draz Nurakks Warder](/npc/157069)
end