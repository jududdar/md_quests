# Captain Berradin


## On NPC Spawn

**Set a timer** named *playdead* for 1 seconds


## Combat

if Captain Berradin enters combat  then


**Stop timer** named *depop*

else


**Set a timer** named *depop* for 50 seconds


e.self:SetAppearance(3);
end



## Timer(s)

if(e.timer == "playdead") then


e.self:SetAppearance(3);


**Stop timer** named *playdead*


**Set a timer** named *depop* for 50 seconds

elseif(e.timer == "depop") then


>**Captain Berradin says:** Uhhhh... I've been poisoned. Carry on the work men. Don't let me die in vain.


if(**spawned NPC:**  [Bodyguard Stoneberg](/npc/116100)) then



eq.get_entity_list():GetMobByNpcTypeID( [Bodyguard Stoneberg](/npc/116100)):Say("Heh, I never liked him anyway...");





**Captain Berradin despawns.**
end
