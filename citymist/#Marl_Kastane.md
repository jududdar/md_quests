# Marl Kastane



[Marl Kastane](/npc/90016) is a level 60 Human Shadow Knight that spawns in [The City of Mist](/zone/90).




## On NPC Spawn



**Set a timer** named *depop* for 4800 seconds


## Dialog

**You say:** `hail`



if( **Faction is** > Dubious) then



>**Marl Kastane says:** Alas, I cannot be the one to carry the sword back to my people as proof in fear they will kill me to possess it for their own. I think a simple trade is in order. Perhaps you have a symbol or token of Lhanrc's that I could take back to the others to ease their worries?

end



## Turn-Ins





if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_647.png" alt="" /> <a
                                href="/item/14384" data-url="14384" class="tooltip-link link">Lhranc's Token</a>) then



>**Marl Kastane says:** Very good, I will go deliver this right away.



Your faction standing with [Truespirit](/faction/404) got worse (<span class='text-danger'>-53</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1195.png" alt="" /> <a
                                href="/item/14383" data-url="14383" class="tooltip-link link">Innoruuk's Curse</a> 

 



**Marl Kastane despawns.**

**This NPC *should* return incorrect items given.**



## Timer(s)

**Stop timer** named *depop*

**Marl Kastane despawns.**


