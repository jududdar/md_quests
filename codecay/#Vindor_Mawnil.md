# Vindor Mawnil


## On NPC Spawn

**Set a timer** named *depop* for 9900 seconds


## Timer(s)

**Vindor Mawnil despawns.**


## Combat

if  Vindor Mawnil enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## On NPC Death


if ( not **spawned NPC:**  [\#Raex Pwodill](/npc/200258) ) then 




local hp = **spawned NPC:**  [\#High Priest Ultor Szanvon](/npc/200245) 





if ( hp and hp.valid ) then



hp:SetBodyType(3, false);




hp:SetSpecialAbility(24, 0); 



hp:SetSpecialAbility(35, 0); 



eq.set_timer("depop", 11700000, hp);

end
