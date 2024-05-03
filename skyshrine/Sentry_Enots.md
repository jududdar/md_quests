# Sentry Enots


## Dialog

**You say:** `hail`



>**Sentry Enots says:** Halt, beyond lies the home of the Kin, servants of the mighty Yelinak.  Be forewarned, those who would be enemies to the Kin, shall find themselves fodder for the cubes.


if(**spawned NPC:**  [Sentry Kcor](/npc/114581)) then



eq.get_entity_list():GetMobByNpcTypeID( [Sentry Kcor](/npc/114581)):Say("You had best speak with the herald before journeying deep into the Sky Shrine.");

end



## Turn-Ins



local helmet =  **You turn in:**  { <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_747.png" alt="" /> <a
                                href="/item/29062" data-url="29062" class="tooltip-link link">Giant Warrior Helmet</a>}



if(helmet > 0) then



repeat



>**Sentry Enots says:** Very good, you are on your way to proving yourself.



Your faction standing with [Claws of Veeshan](/faction/430) got better (<span class='text-success'>+15</span>)




Your faction standing with [Yelinak](/faction/436) got better (<span class='text-success'>+3</span>)




Your faction standing with [Kromzek](/faction/448) got worse (<span class='text-danger'>-7</span>)




 &#127873; **You receive:** 0 (+10000 exp)

 



helmet = helmet - 1;


until helmet == 0;


**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if(e.wp == 10) then


>**Sentry Enots says:** Pardon my intrusion master, but I bring you news from the gate.


if(**spawned NPC:**  [Ziglark Whisperwing](/npc/114343)) then



eq.get_entity_list():GetMobByNpcTypeID( [Ziglark Whisperwing](/npc/114343)):Say("It is all right Enots, what news do you bring me?");



>**Sentry Enots says:** My lord, outsiders have arrived at our gates.  They are of a race I have never seen.  Kcor is with them now attempting to discern their intent.



eq.get_entity_list():GetMobByNpcTypeID( [Ziglark Whisperwing](/npc/114343)):Say("That is alarming indeed, thank you for this information.  Please now return to your post and watch these outsiders.  Guardian Selbbep, please inform the council that I wish a meeting on this latest news.");



>**Sentry Enots says:** Very well, master. My will is but to obey the Kin.



eq.get_entity_list():GetMobByNpcTypeID(114535):Say("Yes my lord, right away.");


elseif(e.wp == 21) then


>**Sentry Enots says:** Herald Ziglark Whisperwing wishes an audience with the outsiders; please do not keep him waiting.


e.self:CastToNPC():StopWandering();
end
