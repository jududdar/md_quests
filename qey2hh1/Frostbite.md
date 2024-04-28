# Frostbite
## Dialog

**You say:** `hail`



>*Frostbite RUFF RUFF*

end

## Turn-Ins




if **You turn in:** [Regurgitonic](/item/12139)


>*Frostbite spits something into your hand.*






* __Faction:__ [Wolves of the North](/faction/320) (2)


* __Faction:__ [Shamen of Justice](/faction/327) (1)


* __Faction:__ [Merchants of Halas](/faction/328) (1)




* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:**  [Koalindl Fish](/item/13383) 

elseif **You turn in:** [Sweaty Shirt](/item/12226)


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