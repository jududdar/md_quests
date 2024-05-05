# Exiled Officer of Marr



[Exiled Officer of Marr](/npc/201441) is a level 45 Shade Warrior that spawns in [Plane of Justice](/zone/201).



## On NPC Spawn

**Set a timer** named *depop* for 120 seconds

**Set a timer** named *fd* for 0 seconds



## Timer(s)

if(e.timer == "depop") then


**Exiled Officer of Marr despawns.**

elseif(e.timer == "fd") then


**Stop timer** named *fd*


e.self:SetAppearance(3); 
end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/29281" data-url="29281" class="tooltip-link link">Box of Souls</a>) then


 &#127873; **You receive:** GiveAll( <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_947.png" alt="" /> <a
                                href="/item/29294" data-url="29294" class="tooltip-link link">Soul Sphere</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1144.png" alt="" /> <a
                                href="/item/29281" data-url="29281" class="tooltip-link link">Box of Souls</a>) 

 

**This NPC *should* return incorrect items given.**
