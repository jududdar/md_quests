# Terror Matriarch



[Terror Matriarch](/npc/204034) is a level 65 Arachnid Warrior that spawns in [Plane of Nightmares](/zone/204).



## Combat

if  Terror Matriarch enters combat  then


**Set a timer** named *hatchling* for 30 seconds

else


**Stop timer** named *hatchling*
end



## Timer(s)

if ( e.timer == "hatchling" ) then





**Spawn NPC:** eq.ChooseRandom( [an abhorrent hatchling](/npc/204475),  [a rapacious hatchling](/npc/204469),  [a voracious hatchling](/npc/204474)) at this location.
end
