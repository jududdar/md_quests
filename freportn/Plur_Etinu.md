# Plur Etinu



[Plur Etinu](/npc/8040) is a level 61 Human GM Cleric that spawns in [North Freeport](/zone/8).



## Dialog

**You say:** `hail`



>**Plur Etinu says:** Your soul is welcome in our temple. The Queen of Love, Erollisi Marr, desires more to join our ranks. This city of Freeport must not stay under the control of  the Freeport Militia. I am here to [cure poison] and [cure disease], or if any [need healing].

**You say:** `cure poison`



>**Plur Etinu says:** Before the Queen of Passion can force the toxin from your system, I shall require 3 bixie stingers to perform the act.

**You say:** `cure disease`



>**Plur Etinu says:** The affliction which has been cast upon you shall be purged from your body, but first I need two portions of zombie flesh to perform the act.

**You say:** `healing`



>**Plur Etinu says:** If it is the power of the passion you require to bind your wounds, then lay down your tribute of 10 gold.
end



## Turn-Ins




if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13074" data-url="13074" class="tooltip-link link">Zombie Skin</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_823.png" alt="" /> <a
                                href="/item/13074" data-url="13074" class="tooltip-link link">Zombie Skin</a>) then 


>**Plur Etinu says:** May the unbridled passion of Erollisi Marr flow through your body.


**Plur Etinu casts:** [Cure Disease](/spell/213) on target.

elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1123.png" alt="" /> <a
                                href="/item/14029" data-url="14029" class="tooltip-link link">Bixie Stinger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1123.png" alt="" /> <a
                                href="/item/14029" data-url="14029" class="tooltip-link link">Bixie Stinger</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1123.png" alt="" /> <a
                                href="/item/14029" data-url="14029" class="tooltip-link link">Bixie Stinger</a>) then 


>**Plur Etinu says:** May the unbridled passion of Erollisi Marr flow through your body.


**Plur Etinu casts:** [Cure Poison](/spell/203) on target.

elseif( **You turn in:** gold = 10) then


>**Plur Etinu says:** May the unbridled passion of Erollisi Marr flow through your body.


**Plur Etinu casts:** [Light Healing](/spell/17) on target.

**This NPC *should* return incorrect items given.**

end