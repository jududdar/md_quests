# Thall Va Kelun



[Thall Va Kelun](/npc/158439) is a level 66 Akheva Rogue that spawns in [Vex Thal](/zone/158).



local Z_LEVEL = 100; 



## Combat

if  Thall Va Kelun enters combat  then


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



**Thall Va Kelun casts:** [Destroy](/spell/1948) on themselves.





elseif ( e.timer == "kill_player" ) then




local hl = e.self:GetHateList();


for ent in hl.entries do



if ( ent.ent:IsClient() ) then




e.self:CastSpell(982, ent.ent:GetID(), 0, 1); 




return;





end
