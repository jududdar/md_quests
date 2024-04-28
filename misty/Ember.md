# Ember
## On NPC Spawn

**Set a timer** named *follow* for 1 seconds
## Timer(s)


if(e.timer == "follow") then


local opponentID =  [Blixkin Entopop](/npc/33066);


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(opponentID);





if(mobtypeID) then



local follow_mob = mobtypeID:GetID();



eq.follow(follow_mob,10);



**Stop timer** named *follow*

end

## Signals

>*Ember clicks at Blixkin happily.*

**Signaled to:**  [Blixkin Entopop](/npc/33066)