# Frostbite
## Dialog

**You say:** `hail`



>*Frostbite RUFF RUFF*

end

## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_584.png" alt="" /> <a
                                href="/item/12139" data-url="12139" class="tooltip-link link">Regurgitonic</a>) then


>*Frostbite spits something into your hand.*






Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+2</span>)


Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+1</span>)




Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_786.png" alt="" /> <a
                                href="/item/13383" data-url="13383" class="tooltip-link link">Koalindl Fish</a> 

 

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/12226" data-url="12226" class="tooltip-link link">Sweaty Shirt</a>) then


>*Frostbite takes a whiff of the sweaty shirt and barks.*


e.other:Ding();


**Set a timer** named *go* for 15 seconds

**This NPC *should* return incorrect items given.**

## Timer(s)

local bad_thief = eq.ChooseRandom(12190,12190,12190,12190,12190,12191);

local random_x = eq.ChooseRandom(-3461,-3902,-4011);

local random_y = eq.ChooseRandom(-1457,-3240,-1362);



if(e.timer == "go") then


**Stop timer** named *go*


**Set a timer** named *depop* for 1200 seconds


eq.unique_spawn(bad_thief,11,0,random_x,random_y,10,0);


e.self:SetRunning(true);


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID(bad_thief);





if(mobtypeID) then



local follow_mob = mobtypeID:GetID();



eq.follow(follow_mob);


elseif(e.timer == "depop") then


**Frostbite despawns.**
end

## Signals

eq.stop_follow();

e.self:SetRunning(false);

eq.move_to(-2236,-3532,34,110);

**Stop timer** named *depop*