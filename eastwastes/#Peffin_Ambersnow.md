# Peffin Ambersnow



[Peffin Ambersnow](/npc/116038) is a level 50 Coldain Rogue that spawns in [Eastern Wastes](/zone/116).



## On NPC Spawn

**Set a timer** named *depop* for 265 seconds


## Combat

if Peffin Ambersnow enters combat  then


**Peffin Ambersnow shouts:** <span class="text-danger">Take me if you can outlander! Your hunt ends here...I hope you enjoy the taste of Kromrif steel!</span>


if(not eq.is_paused_timer("depop")) then



eq.pause_timer("depop");


else


eq.resume_timer("depop");
end



## Timer(s)


>**Peffin Ambersnow says:** The cowards seem to have fled friends, thank you for your protection.

**Despawn all instances of:**  [\#Kromrif Elite](/npc/116040)

**Peffin Ambersnow despawns.**