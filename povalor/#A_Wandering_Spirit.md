# A Wandering Spirit



[A Wandering Spirit](/npc/208209) is a level 70 Human Warrior that spawns in [Plane of Valor](/zone/208).









## Dialog

**You say:** `hail`



>*A Wandering Spirit groans in extreme anguish. '[Help] me.'*




**You say:** `help`



>**A Wandering Spirit says:** My resting grounds have been desecrated. I now lie awake unable to rest with my fellow brethren. My soul is bound to this area for all of eternity. Until my [belongings] are brought back I cannot rest.


**You say:** `belongings`



>**A Wandering Spirit says:** Many different things were taken, but I'm mainly concerned with my [amulet] and my family's crescent symbol. Bring these articles back into my possession and I'll return back to my state of rest.


**You say:** `amulet`



>**A Wandering Spirit says:** The amulet was given to me after passing the Trials many many generations ago.  It is a part of every soldier who has passed the trials, it is a part of my very being.
end



## Turn-Ins





if (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_754.png" alt="" /> <a
                                href="/item/20605" data-url="20605" class="tooltip-link link">Crescent Symbol of Rhaj</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1056.png" alt="" /> <a
                                href="/item/20606" data-url="20606" class="tooltip-link link">Righteous Amulet of Marr</a>  ) then 


>*A Wandering Spirit quickly grabs the amulet and crescent symbol before speaking. 'At long last! I can now rest in peace along with my fellow brethren. Thank you Soandso. May the might of Marr follow you wherever you may go.'*


 &#127873; **You receive:** 0 

 


**A Wandering Spirit despawns.**




elseif (  **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_805.png" alt="" /> <a
                                href="/item/20608" data-url="20608" class="tooltip-link link">Unwavering Shield of Faith</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1173.png" alt="" /> <a
                                href="/item/20607" data-url="20607" class="tooltip-link link">Unwavering Sword of Faith</a>  ) then 


>*A Wandering Spirit looks at you with great surprise. 'It's been quite some time since I've been without my weaponry. Thank you for returning them to me Soandso.'*


 &#127873; **You receive:** 0 

 


**A Wandering Spirit despawns.**



**This NPC *should* return incorrect items given.**
;


## On NPC Spawn

**Set a timer** named *depop* for 100 seconds


## Timer(s)

if ( e.timer == "depop" ) then


**A Wandering Spirit despawns.**
end
