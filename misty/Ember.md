# Ember

[Ember](/npc/33065) is a level 1 Beetle Warrior that spawns in [Misty Thicket](/zone/33).

Their primary faction is [Merchants of Rivervale](/faction/292).

## On NPC Spawn
**Set a timer** named *follow* for 1 seconds




## Timer(s)

if(e.timer == "follow") then
local opponentID = 33066;
local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(opponentID);

if(mobtypeID) then
local follow_mob = mobtypeID:GetID();
eq.follow(follow_mob,10);
**Stop timer** named *follow*






## Signals
>*Ember clicks at Blixkin happily.*
**Signaled to:**  [Blixkin Entopop](/npc/33066)
