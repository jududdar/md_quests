# Iceberg



[Iceberg](/npc/30062) is a level 35 Bear Warrior that spawns in [Everfrost Peaks](/zone/30).



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




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_816.png" alt="" /> <a
                                href="/item/12221" data-url="12221" class="tooltip-link link">Lion Delight</a>) then


>*Iceberg growls with happiness and licks your face.  Just enough time to swipe the sweaty shirt from his collar!!  Iceberg then runs off to enjoy his lion delight!!*


**Signaled to:**  [Tundra Jack](/npc/30061)





Your faction standing with [Wolves of the North](/faction/320) got better (<span class='text-success'>+2</span>)


Your faction standing with [Shamen of Justice](/faction/327) got better (<span class='text-success'>+1</span>)


Your faction standing with [Merchants of Halas](/faction/328) got better (<span class='text-success'>+1</span>)


Your faction standing with [Steel Warriors](/faction/311) got better (<span class='text-success'>+1</span>)


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_632.png" alt="" /> <a
                                href="/item/12226" data-url="12226" class="tooltip-link link">Sweaty Shirt</a> (+1000 exp)

 

**This NPC *should* return incorrect items given.**


