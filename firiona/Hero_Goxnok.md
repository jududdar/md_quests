# Hero Goxnok



[Hero Goxnok](/npc/84319) is a level 25 Iksar Shadow Knight that spawns in [Firiona Vie](/zone/84).




## Dialog

**You say:** `charasis tome`



>**Hero Goxnok says:** The Charasis Tome has been scribed and now another copy exists. The traitor obviously wants to keep a copy for himself. I am told you will deliver both copies to Lord Qyzar along with your zealot khukri and you shall be awarded that of a crusader. Let us rest for a minute and then I shall show you the meeting place.


eq.move_to(-1856,589,146,36,true);


e.self:SetAppearance(1);


>**Hero Goxnok says:** Come along. If we get separated, look for the humanoid wolf camp and beyond the tunnel, you shall find the meeting place of the spider riders and the traitor.


**Set a timer** named *Talk1* for 180 seconds
end



## Signals

if(e.signal == 1) then


**Spawn NPC:**  [\#Hero Goxnok](/npc/84401) at this location.


**Hero Goxnok despawns.**
end



## Timer(s)

if(e.timer == "Talk1") then


>*Hero Goxnok stops abruptly and shudders with fear. 'Look!! There, past the wolf people. Near an ancient tunnel can be found the meeting place. I fear we may be too late. I thought I saw a shadow dash from the tunnels, but I did not see any spider riders. We'll see when we reach it.'*


**Stop timer** named *Talk1*


**Set a timer** named *Talk2* for 30 seconds

if(e.timer == "Talk2") then


>*Hero Goxnok looks over at you and sizes you up before continuing on. He says, 'We should continue, follow me.'*


**Stop timer** named *Talk2*
end



## Turn-Ins



**This NPC *should* return incorrect items given.**






