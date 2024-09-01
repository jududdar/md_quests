# Broon

[Broon](/npc/15051) is a level 23 Giant Warrior that spawns in [Eastern Plains of Karana](/zone/15).

Their primary faction is [Cyclops](/faction/68).

## On NPC Death

if(math.random(1,100) < 50) then

brofath = 15138;

else

brofath = 15160;



eq.unique_spawn(brofath,7,0,807,2105,135,0);

