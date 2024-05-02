# Paralin Notion
## Dialog


local qglobals = eq.get_qglobals(e.other);

local questState = tonumber(qglobals.pov_orb_quest or 0);


**You say:** `hail`



>**Paralin Notion says:** I knew you'd come through for us Soandso. I knew from the very beginning. The Battalion salutes you.


return;

if ( questState >= 5 ) then


return;



elseif ( questState == 4 ) then




**You say:** `hail`




>**Paralin Notion says:** I'm sorry the Master Sergeant was unable to help you. Perhaps you should [prove] yourself before you attempt to jump 'into the fire' so to speak.






**You say:** `prove`




>**Paralin Notion says:** We've been running into a lot of problems lately with the razorfiends and the planarian larvae. Many soldiers have been getting sick because of the infestations that they cause. Capture the hearts of a razorfiend, a crystalline spider and a planarian larvae and bring them back to me. Our squad had enough problems capturing this small razorfiend here. This will become your first so called 'Trial' Soandso. It should be enough to prove your worth.




elseif ( questState == 2 or questState == 3 ) then




**You say:** `hail`




>**Paralin Notion says:** You're either [brave], or you're [stupid].





**You say:** `brave`




>**Paralin Notion says:** That you are. Perhaps you'd be interested in helping our [company].




**You say:** `stupid`

















**You say:** `company`







>**Paralin Notion says:** We're a part of the Battalion of Marr. We're soldiers from Che Virtuson. We were dispatched to this part of the Plane of Valor to eliminate an age old target. Unfortunately, due to some recent events our mission has been placed on hold and our [squad] has been asked to remain behind.





**You say:** `squad`







>**Paralin Notion says:** We are apart of Ducee Tapferson. Our squad is known for our bravery. We were successful in capturing this [razorfiend] earlier today. You've shown some bravery as well my friend and that is the reason I request your [assistance].





**You say:** `assistance`







>**Paralin Notion says:** Many of us here are anxious to leave. Many wish to regroup with the rest of our company. Other wish to go back to the Halls to complete the [Trials].





**You say:** `razorfiend`







>**Paralin Notion says:** These vile beasts live in the caves west of here.





**You say:** `trials`







>**Paralin Notion says:** The Trials are overseen by the Heroes of Marr. It's these Trials that allow us to rise in rank. Only those who have passed the trials are able to enter the Temple of Marr. Now if you wish to aid us I must ask you to do a few [things].





**You say:** `things`







>**Paralin Notion says:** You must find the Master Sergeant and tell him that you are here to aid the cause.



eq.set_global("pov_orb_quest", "3", 1, "H6");


else


**You say:** `hail`




>*Paralin Notion nods in your direction.*

end

## Turn-Ins

local questState = tonumber(eq.get_qglobals(e.other).pov_orb_quest or 0);





if (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/25597" data-url="25597" class="tooltip-link link">A Crystalline Spider's Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/25598" data-url="25598" class="tooltip-link link">A Razorfiend's Heart</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1003.png" alt="" /> <a
                                href="/item/25599" data-url="25599" class="tooltip-link link">A Planarian Larvae's Heart</a>  ) then 




if ( questState >= 4 ) then






>*Paralin Notion looks at you with surprise. 'Very good my friend. You've definitely proven yourself. Find the Master Sergeant. He should be able to help you this time.'*







 &#127873; **You receive:** 0 (+1 exp)

 



if ( questState == 4 ) then




eq.set_global("pov_orb_quest", "5", 1, "H24");




else



>*Paralin Notion looks at you in disgust and wonders why you did that.*


**This NPC *should* return incorrect items given.**
;