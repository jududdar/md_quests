# Gamali


## Dialog

**You say:** `hail`



>*Gamali Glances up at you for a moment and then grunts and turns back toward the water.*
end



## Turn-Ins



local bottles = 0



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>) then


bottles = 4;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>) then


bottles = 3;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>) then


bottles = 2;

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_704.png" alt="" /> <a
                                href="/item/16598" data-url="16598" class="tooltip-link link">Bottle</a>) then


bottles = 1;



if(bottles > 0) then


repeat



>*Gamali leans over and fills the bottle with cool clear liquid. Gamali says, 'So Merchant Ahlam has you doing his errands now does he? Well, here's your water. I can assure you it's of good quality.' She turns away and begins staring out into the distance.*



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_688.png" alt="" /> <a
                                href="/item/31761" data-url="31761" class="tooltip-link link">Bottle of fresh water</a> 

 



bottles = bottles - 1;


until bottles == 0


bottles = 0;

**This NPC *should* return incorrect items given.**
