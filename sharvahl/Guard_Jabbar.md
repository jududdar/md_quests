# Guard Jabbar



[Guard Jabbar](/npc/155085) is a level 50 Vah Shir Warrior that spawns in [The City of Shar Vahl](/zone/155).



## Dialog

**You say:** `Hail`



>**Guard Jabbar says:** Greetings! You wouldn't happen to be the one delivering the tea I requested from Ahlan, are you?
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_608.png" alt="" /> <a
                                href="/item/31766" data-url="31766" class="tooltip-link link">Crate of Tea</a>) then


>**Guard Jabbar says:** Ah the tea! I've been anxiously awaiting your arrival Soandso! We'd almost run out of this wonderful Gravel leaf tea. Take this seal back to Ahlam, and give him my thanks.


eq.start(37);


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_646.png" alt="" /> <a
                                href="/item/31775" data-url="31775" class="tooltip-link link">Jabbar's seal</a> (+2000 exp)

 

**This NPC *should* return incorrect items given.**



## Arrive at Waypoint Script

if(e.wp == 1) then


>**Guard Jabbar says:** Time for dinner you wretches!

elseif(e.wp == 3) then


>**Guard Jabbar says:** Wake up maggot, time for dinner!' Guard Jabbar places the meal on the endo fhte bed. The grimling feasts hungrily on it, drinking all the sedative tea in one gulp.

elseif(e.wp == 4) then


>*Guard Jabbar kicks the sleeping grimling and sets down another meal tray on the stone bed.*

elseif(e.wp == 7) then


>*Guard Jabbar grunts at the grimling sitting in the corner and hands him the tray. The grimling fingers the food suspiciously for a moment and then begins to eat.*

elseif(e.wp == 8) then


if(**spawned NPC:**  [Gendalic](/npc/155209)) then



>**Guard Jabbar says:** Get up Gendalic, time for your evening meal.



eq.get_entity_list():GetMobByNpcTypeID( [Gendalic](/npc/155209)):Emote("glances up from the ground but ignores Guard Jabbar and continues starying at the wall. He appears to be studying something. perhaps the design of the stones in the wall.");


elseif(e.wp == 9) then


if(**spawned NPC:**  [Gendalic](/npc/155209)) then



>*Guard Jabbar growls sending a shriver of fear up your spine. He methodically sets the tray down on the ledge and turns to face Gendalic. Quick as lightning, Guard Jabbar strikes Gendalic hard in teh lower back, causing him to lurch forward and smack his face against the wall.*



eq.get_entity_list():GetMobByNpcTypeID( [Gendalic](/npc/155209)):Emote("cries out in pain and  and falls to the floor of the cell, guarding his face with his hands.  Guard Jabbar glares at him and mutters something under his breath as he turns and walks out of the cell.");


elseif(e.wp == 13) then


eq.stop();
end
