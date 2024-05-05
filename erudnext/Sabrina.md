# Sabrina



[Sabrina](/npc/24056) is a level 1 Launch Warrior that spawns in [Erudin](/zone/24).



## Signals 



if(e.signal == 1) then 


 

eq.start(21); 


 
elseif(e.signal == 2) then 


 

eq.stop();
 


## On NPC Spawn

eq.spawn_condition("erudnext",1,0);

eq.spawn_condition("erudnext",2,0);
end