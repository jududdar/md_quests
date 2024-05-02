# Bondl Felligan
## Dialog

local qglobals = eq.get_qglobals(e.self,e.other);



**You say:** `hail`



>*Bondl Felligan burps loudly in your face and says, 'Bah! Leave me be, fool! You have nothin' I want and I certainly have nothin' you want.*

**You say:** `you can buy booze`



>*Bondl Felligan suddenly becomes completely sober and says, 'Very well, shaman, please come with me.'*


**Spawn NPC:**  [a greater spirit](/npc/8117) at (**y:** 66, **x:** 62)


if(e.self:GetX() == 407 and e.self:GetY() == 235) then



eq.stop();



eq.start(14);


elseif(e.self:GetX() == 589 and e.self:GetY() == 472) then



eq.stop();



eq.start(15);

end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_961.png" alt="" /> <a
                                href="/item/1665" data-url="1665" class="tooltip-link link">Tiny Gem</a>) then 


>**Bondl Felligan says:** WOW, thanks! This must be worth a fortune! I could drink for a month after sellin' this to one of them fool merchants. I'm going to see how much I can get for it right now!


Your faction standing with [Truespirit](/faction/404) got better (<span class='text-success'>+100</span>)


 &#127873; **You receive:** 0 (+1000 exp)

 


eq.set_global("shamanbondl","1",1,"F");


eq.start(13);

**This NPC *should* return incorrect items given.**
;
## Arrive at Waypoint Script

if(e.wp == 6 and e.self:GetX() == 407 and e.self:GetY() == 235) then


>**Bondl Felligan says:** What!? You don't approve of me buyin' some drinks with this gem? Who the heck are you to offer me a gift and order me what to do with it? Is this some kinda conditional kindness? Well? Are you gonna let me buy some booze with this or not?

elseif(e.wp == 12 and e.self:GetX() == 589 and e.self:GetY() == 472) then


eq.stop();


