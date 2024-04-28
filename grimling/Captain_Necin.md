# Captain Necin
## Dialog

**You say:** `hail`



>**Captain Necin says:** Hello, Soandso. I'm looking for an accomplished soldier to help me carry out a very dangerous mission. If you know of one please have them report to me at once.

**You say:** `soldier`



>**Captain Necin says:** Very well, acquire a chest of valor and fill it with the medals you receive from scouts Husman, Danarin, and Derin. Give me the resulting soldier's chest and I will reveal the details of my mission.
end

## Turn-Ins





if (  **You turn in:** [Soldier's Chest](/item/4397)


>**Captain Necin says:** Take this map and study it carefully. The mission we are preparing to embark upon will make your previous raids seem like child's play. Many friendly forces will need to help us to achieve our objectives, two dozen soldiers as powerful as me to be exact. When you have selected and briefed the troops that will carry out the offensive, give me the map and I will lead the assault.


 **You receive:**  [Map of Grimling Forest](/item/4398) 




elseif (  **You turn in:** [Map of Grimling Forest](/item/4398)


>**Captain Necin says:** Form up and follow me, I have an officer meeting us just outside the outpost. I'll finish briefing you all there.


 **You receive:** 0 (+50000 exp)


**Spawn NPC:**  [\#Captain Necin](/npc/167689) at this location.


**Spawn NPC:**  [\#Sergeant Jherum](/npc/167691) at (**y:** -1075, **x:** -489)


**Captain Necin despawns.**

**This NPC *should* return incorrect items given.**
;