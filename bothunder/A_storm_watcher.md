# A storm watcher



[A storm watcher](/npc/209113) is a level 63 Nightmare Gargoyle Warrior that spawns in [Bastion of Thunder](/zone/209).



## Signals

local client = eq.get_entity_list():GetClientByID(e.signal);



if ( client and client.valid ) then


if ( e.self:CalculateDistance(client:GetX(), client:GetY(), client:GetZ()) < 150 ) then



e.self:AddToHateList(client, 1);

end
