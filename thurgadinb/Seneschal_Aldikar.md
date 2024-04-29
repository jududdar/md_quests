# Seneschal Aldikar
## Dialog

**You say:** `hail`



>**Seneschal Aldikar says:** And a good day to you, " .. e.other:Race() .. ". I must say that I'm impressed that your people were even able to make it to our continent, let alone survive the frigid temperatures of it. I am Seneschal Aldikar, Commander of the Armies of Thurgadin, known by some as the Sword of the Dain. My armies are currently undergoing intensive training and are ready for a full assault on Kael Drakkel as soon as his majesty gives the order.

**You say:** `accept this task`



>**Seneschal Aldikar says:** In this box, place the accursed dirk of the fallen Rodrick. With it combine the heads of every traitor you dispose of. When this is done give the box and the velium insignia ring to the Dain directly. On behalf of the crown and all good Coldain, I thank you ... May Brell be with you.


**You receive:**  [Traitors Bane Box](/item/17055)
end

## Turn-Ins





if( **You turn in:** [Velium Coldain Insignia Ring](/item/30164)) then


if(e.self:GetX() == -3 and e.self:GetY() == 693) then



>**Seneschal Aldikar says:** 'Well done, Soandso, I have heard of your victory over the Ry\`Gorr. If you are willing to assist the crown further please follow me.



 **You receive:**  [Velium Coldain Insignia Ring](/item/30164) 



e.self:CastToNPC():AssignWaypoints(14);


else



>**Seneschal Aldikar says:** Soandso I must speak to the Dain before I instruct you further. Please speak to me while the royal court is in session.



 **You receive:**  [Velium Coldain Insignia Ring](/item/30164) 


**This NPC *should* return incorrect items given.**

## Arrive at Waypoint Script

if(e.wp == 15) then


>**Seneschal Aldikar says:** Please, shut the door behind you. What I am about to share with you must not be overheard.

elseif(e.wp == 16) then


>**Seneschal Aldikar says:** My army stands prepared to launch an assault on Kael itself, but one task must be completed before this can happen.

elseif(e.wp == 17) then


>**Seneschal Aldikar says:** It seems Rodrick was not alone in his treachery. There is a faction of Coldain who believe that a treaty should be signed with the Kromrif, ending our hostilities with them. This, of course, is impossible. If there is one thing our history here has taught us, it is that the Kromrif simply cannot be trusted.

elseif(e.wp == 18) then


>**Seneschal Aldikar says:** These traitors are poisoning the minds of our citizens, promising great rewards to those who will betray the Dain. It will take the unbiased eye of an outlander to flush out the masterminds behind this plan. Once again we turn to you.

elseif(e.wp == 19) then


>**Seneschal Aldikar says:** Will you accept this task, outlander?

elseif(e.wp == 20) then


>**Seneschal Aldikar says:** Farewell.

elseif(e.wp == 31) then


e.self:CastToNPC():StopWandering();
end
