# Raex Pwodill



[Raex Pwodill](/npc/200258) is a level 70 Knight of Pestilence Warrior that spawns in [The Crypt of Decay](/zone/200).



## On NPC Spawn

**Set a timer** named *depop* for 9900 seconds


## Timer(s)

**Raex Pwodill despawns.**


## Combat

if  Raex Pwodill enters combat  then


eq.pause_timer("depop");

else


eq.resume_timer("depop");
end



## On NPC Death


if ( not **spawned NPC:**  [\#Vindor Mawnil](/npc/200261) ) then 




local hp = **spawned NPC:**  [\#High Priest Ultor Szanvon](/npc/200245) 





if ( hp and hp.valid ) then



hp:SetBodyType(3, false);




hp:SetSpecialAbility(24, 0); 



hp:SetSpecialAbility(35, 0); 



eq.set_timer("depop", 11700000, hp);

end
