# Gash Flockwalker



[Gash Flockwalker](/npc/1138) is a level 8 Half Elf Druid that spawns in [South Qeynos](/zone/1).



## Dialog

**You say:** `hail`



>**Gash Flockwalker says:** Good day to you. Your city of stone walls is quite magnificent. Still, the glory of Surefall Glade puts this city to shame.

**You say:** `assassin`



>**Gash Flockwalker says:** What!!?  Must be an Unkempt Druid Assassin nearby!!  Find him and slay him.  I am sure he stands to make a FORTUNE!  I believe the assassin may be carrying some sort of [black wood chip].


**Spawn NPC:**  [Raffel Minnmorn](/npc/1179) at (**y:** 222, **x:** -100)


**You say:** `black wood chip`



>**Gash Flockwalker says:** That is the mark of an Unkempt Druid.  Long ago there was a tree in Norrath we called the Great Tunarbos.  Legend says it spawned all the woodlands of Norrath.  Many centuries ago, long before the Combine Era, the Great Tunarbos was burned to the ground by unknown means.  The ancient rangers kept what little of the great tree they could find.  To make it short, all Unkempt Druids now carry burned wood chips to represent the great tree.  They are not real.  Take any black wood chips to Gerael Woodone in Surefall Glade.
end



## Arrive at Waypoint Script

if(e.wp == 17) then


>**Gash Flockwalker says:** Even the beauty of the ocean pales in comparison to the towering pines of Surefall Glade.

elseif(e.wp == 27) then


>**Gash Flockwalker says:** I have had a tree sap from Surefall Glade which tastes better than this ale.
end
