# Lord Rak\`Ashiir



[Lord Rak\`Ashiir](/npc/90013) is a level 55 Iksar Spirit Wizard that spawns in [The City of Mist](/zone/90).



## On NPC Spawn

**Set a timer** named *faction* for 5 seconds


## Timer(s)

if(e.timer == "faction") then


eq.set_proximity(e.self:GetX() - 45, e.self:GetX() + 45, e.self:GetY() - 45, e.self:GetY() + 45, e.self:GetZ() -5, e.self:GetZ() +5);
end

function event_enter(e)

if **Faction** <  Ally +700 and e.other:Admin() < 80) then


e.self:AddToHateList(e.other,1);
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1160.png" alt="" /> <a
                                href="/item/1673" data-url="1673" class="tooltip-link link">Child's Tear</a>) then


if **Faction** >= Ally +700 then



>*Lord Rak-Ashiir looks down at the tear in his hand and says 'A minion of my god came to me one night. I knew it was of Cazic-Thule as I was frozen in terror. My mind screamed for me to flee but my body would not respond. The being took my daughter and vanished to only he knew where. When I regained control of my body and thoughts, I felt nothing but betrayal. I don't care anymore about anything. If you want repentance then slay me, Soandso.*



Your faction standing with [Truespirit](/faction/404) got better (<span class='text-success'>+100</span>)



 &#127873; **You receive:** 0 

 



**Spawn NPC:**  [\#Lord Rak\`Ashiir ](/npc/90014) at this location.



**Lord Rak-Ashiir despawns.**


else



>**Lord Rak-Ashiir says:** You need to prove your dedication to our cause before I can discuss such matters with you.



**Lord Rak-Ashiir attacks you.**



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1160.png" alt="" /> <a
                                href="/item/1673" data-url="1673" class="tooltip-link link">Child's Tear</a> 

 



**This NPC *should* return incorrect items given.**
