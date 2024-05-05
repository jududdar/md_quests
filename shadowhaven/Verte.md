# Verte



[Verte](/npc/150173) is a level 30 Human Shopkeeper that spawns in [Shadow Haven](/zone/150).



## Arrive at Waypoint Script

if (e.wp == 1) then


>**Verte says:** Ok Talor, I'm off to the keep to deposit our daily earnings. Watch the shop while I'm gone, will ya mate.

elseif (e.wp == 11) then


>**Verte says:** Hello there Faloensar, having a good day I would hope.


**Signaled to:**  [Fordel Keeper Faloensar](/npc/150286)

elseif (e.wp == 12) then


>**Verte says:** Ah well just here to make my daily deposit then it's back to the bar for me. Had quite a brawl last night and still got some cleaning up to do. Those crazy Dwarves I tell you, get a few drinks in them and they want to take on the world or the closest Barbarian.


**Signaled to:**  [Fordel Keeper Faloensar](/npc/150286)

elseif (e.wp == 13) then


>**Verte says:** Ill try my best! Nice doing business with you as always. Take care


**Signaled to:**  [Fordel Keeper Faloensar](/npc/150286)
end



## Dialog

**You say:** `hail`



if **Faction** >= Indifferent then



>**Verte says:** Hey there Soandso. We carry many Shadowhaven exclusive brews here in our tavern. Pull up a barstool and enjoy an ale or two.


else



>**Verte says:** Due to the problems we have had lately with dishonorable visitors to the Haven we require all newcomers to see Daloran and Mistala for some simple tasks to prove that your intentions are good. I hope to see you soon.

end
