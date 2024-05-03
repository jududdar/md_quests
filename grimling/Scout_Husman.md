# Scout Husman


## Dialog

**You say:** `hail`



>**Scout Husman says:** Hello Soandso, It's a good day for a raid, wouldn't you agree?

**You say:** `agree`



>**Scout Husman says:** Well, if you have the courage, round up about six people of my strength and, when you're ready to begin, give me a polished acrylia sphere. I'll lead you on a raid against a grimling camp not far from here. If we're strong enough to take over the camp there will be a good chance for treasure.

**You say:** `raid`



>**Scout Husman says:** 'I know the way to a grimling camp close to here. If you have about six people of my strength we have a good chance of taking it over. With luck, a grimling officer will take part in their counterattack, and they can carry valuable treasure indeed. Fetch me a polished acrylia sphere and I'll guide you.
end



## Turn-Ins

if ( **spawned NPC:**  [\#\#Scout Husman](/npc/167679) ) then 


return;







if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_734.png" alt="" /> <a
                                href="/item/3681" data-url="3681" class="tooltip-link link">Polished Acrylia Sphere</a>) then 


 &#127873; **You receive:** 0 (+1000 exp)

 


>**Scout Husman says:** Nothing better than killing grimlings for the king! Follow me closely and fight well. Make certain that I survive, for if I perish the mission will be a failure.


**Spawn NPC:**  [\#Scout Husman](/npc/167034) at this location.


**Scout Husman despawns.**

**This NPC *should* return incorrect items given.**
