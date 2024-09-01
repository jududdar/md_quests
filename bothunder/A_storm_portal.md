# A storm portal

[A storm portal](/npc/209034) is a level 40 BoT Portal Warrior that spawns in [Bastion of Thunder](/zone/209).

## Signals
if ( e.signal == 1 ) then
>*A storm portal glows with power as several large silhouettes begin to take shape inside.*
eq.spawn2(
eq.ChooseRandom(209124, 209123, 209125, 209130), 
0, 0, e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0
);

