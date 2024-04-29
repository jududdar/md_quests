# Iceberg
## Dialog

**You say:** `hail`



>**Iceberg says:** Rrrroarrrrr...

end

## On NPC Spawn

**Set a timer** named *follow* for 1 seconds
## Timer(s)

if(e.timer == "follow") then


local mobtypeID =  eq.get_entity_list():GetMobByNpcTypeID( [Tundra Jack](/npc/30061));





if(mobtypeID) then



local follow_mob = mobtypeID:GetID();



eq.follow(follow_mob);



**Stop timer** named *follow*

end

## Combat

if(e.joined == true) then


>**Iceberg says:** Grrroarrr !!


**Signaled to:**  [Tundra Jack](/npc/30061)

else


**Signaled to:**  [Tundra Jack](/npc/30061)
end

## Turn-Ins




if( **You turn in:** [Lion Delight](/item/12221)) then


>*Iceberg growls with happiness and licks your face.  Just enough time to swipe the sweaty shirt from his collar!!  Iceberg then runs off to enjoy his lion delight!!*


**Signaled to:**  [Tundra Jack](/npc/30061)





* __Faction:__ [Wolves of the North](/faction/320) (2)


* __Faction:__ [Shamen of Justice](/faction/327) (1)


* __Faction:__ [Merchants of Halas](/faction/328) (1)


* __Faction:__ [Steel Warriors](/faction/311) (1)


 **You receive:**  [Sweaty Shirt](/item/12226) (+1000 exp)

**This NPC *should* return incorrect items given.**


