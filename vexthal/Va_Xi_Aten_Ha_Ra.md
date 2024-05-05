# Va Xi Aten Ha Ra



[Va Xi Aten Ha Ra](/npc/158440) is a level 66 Akheva Warrior that spawns in [Vex Thal](/zone/158).



local Z_LEVEL = 100; 



## Combat

if  Va Xi Aten Ha Ra enters combat  then


**Set a timer** named *cheat_check* for 120 seconds

else


**Stop timer** named *cheat_check*


**Stop timer** named *kill_player*
end



## Timer(s)

if ( e.timer == "cheat_check" ) then




if ( e.self:GetZ() < Z_LEVEL ) then



eq.stop_timer(e.timer);



**Set a timer** named *kill_player* for 0 seconds



**Va Xi Aten Ha Ra casts:** [Destroy](/spell/1948) on themselves.





elseif ( e.timer == "kill_player" ) then




local hl = e.self:GetHateList();


for ent in hl.entries do



if ( ent.ent:IsClient() ) then




**Signaled to:**  [Stop Cheating](/npc/158480)




return;





end
