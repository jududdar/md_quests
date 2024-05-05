# Sergeant Johson Popoah



[Sergeant Johson Popoah](/npc/208015) is a level 67 Valorian Warrior that spawns in [Plane of Valor](/zone/208).



## Dialog



**You say:** `hail`





local questState = tonumber(eq.get_qglobals(e.other).pov_orb_quest or 0);



if ( questState == 0 ) then



>**Sergeant Johson Popoah says:** State your business or leave our [compound].



if ( questState == 0 ) then




eq.set_global("pov_orb_quest", "1", 1, "H6");




else



>**Sergeant Johson Popoah says:** Leave now before there is bloodshed.



if ( questState == 1 ) then




eq.set_global("pov_orb_quest", "2", 1, "H6");







**You say:** `compound`



>**Sergeant Johson Popoah says:** This is the primary command center for Che Virtuson. We fall under the leadership and guidance of Captain Ryglot. I must now ask you to leave.
end
