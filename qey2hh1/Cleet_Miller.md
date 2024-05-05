# Cleet Miller



[Cleet Miller](/npc/12108) is a level 32 Human Shopkeeper that spawns in [Western Plains of Karana](/zone/12).



## Arrive at Waypoint Script

if(e.wp == 1) then


e.self:SetRunning(false);

elseif(e.wp == 6) then


>*Cleet Miller gathers up a bale of straw*


**Spawns on ground:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1145.png" alt="" /> <a
                                href="/item/13990" data-url="13990" class="tooltip-link link">Sack of Hay</a> at (**y:** - <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_576.png" alt="" /> <a
                                href="/item/3583" data-url="3583" class="tooltip-link link">Blade of Shadowed Flame</a>, **x:** -4632)


e.self:SetRunning(true);
end


