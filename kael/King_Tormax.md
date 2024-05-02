# King Tormax



## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**King Tormax says:** Greetings, Soandso. You know who I am, but I only vaguely know of you. My purpose is simple, I will rule these lands like my father, and my grandfather before him. All tasks but two are inconsequential to me.


elseif **Faction** >= Indifferent then



>**King Tormax says:** You may have proven yourself worthy to serve the Kromzek, Soandso, but you have yet to earn my trust.




else



>**King Tormax says:** Why do I even suffer such lesser beings in my presence? Remove yourself, " .. e.other:Race() .. ", else I'll have my guards relieve you of your head.


**You say:** `task`



if **Faction** >= Amiable then



>**King Tormax says:** The tasks are simple, " .. e.other:Race() .. ". I wish the death of the other 'powers' of this frozen waste land. If you are able to destroy either of my mortal foes, bring me proof of your exploits and you will be known as the hero of Kael Drakkel.


elseif **Faction** >= Indifferent then



>**King Tormax says:** You may have proven yourself worthy to serve the Kromzek, Soandso, but you have yet to earn my trust.




else



>**King Tormax says:** Why do I even suffer such lesser beings in my presence? Remove yourself, " .. e.other:Race() .. ", else I'll have my guards relieve you of your head.


**You say:** `power`



if **Faction** >= Amiable then



>*King Tormax laughs deeply. 'I speak of the foolish old dragon Yelinak and that pitiful Dain Frostreaver.'*


elseif **Faction** >= Indifferent then



>**King Tormax says:** You may have proven yourself worthy to serve the Kromzek, Soandso, but you have yet to earn my trust.




else



>**King Tormax says:** Why do I even suffer such lesser beings in my presence? Remove yourself, " .. e.other:Race() .. ", else I'll have my guards relieve you of your head.


**You say:** `yelinak`



if **Faction** >= Amiable then



>**King Tormax says:** Yelinak's mate was slain by my ancestor Porlos single-handedly.  Since that time, the great beast has stalked my line.  Unable to slay any of us...


elseif **Faction** >= Indifferent then



>**King Tormax says:** You may have proven yourself worthy to serve the Kromzek, Soandso, but you have yet to earn my trust.




else



>**King Tormax says:** Why do I even suffer such lesser beings in my presence? Remove yourself, " .. e.other:Race() .. ", else I'll have my guards relieve you of your head.


**You say:** `dain`



if **Faction** >= Amiable then



>**King Tormax says:** Dain Frostreaver is the leader of the disgusting Coldain.  Some day they will be cleansed from this holy land.


elseif **Faction** >= Indifferent then



>**King Tormax says:** You may have proven yourself worthy to serve the Kromzek, Soandso, but you have yet to earn my trust.




else



>**King Tormax says:** Why do I even suffer such lesser beings in my presence? Remove yourself, " .. e.other:Race() .. ", else I'll have my guards relieve you of your head.

end

## Turn-Ins







if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_990.png" alt="" /> <a
                                href="/item/30501" data-url="30501" class="tooltip-link link">Dain Frostreaver's Head</a>) then 


if( **Faction is** > Threatening) then



Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+500</span>)



Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+500</span>)



Your faction standing with [Yelinak](/faction/436) got worse (<span class='text-danger'>-250</span>)



Your faction standing with [Dain Frostreaver IV](/faction/405) got worse (<span class='text-danger'>-250</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_718.png" alt="" /> <a
                                href="/item/25858" data-url="25858" class="tooltip-link link">Belt of Dwarf Slaying</a> (+500000 exp)

 


elseif( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_1231.png" alt="" /> <a
                                href="/item/24984" data-url="24984" class="tooltip-link link">Yelinak's Head</a>) then 


if( **Faction is** > Threatening) then



Your faction standing with [King Tormax](/faction/429) got better (<span class='text-success'>+500</span>)



Your faction standing with [Kromzek](/faction/448) got better (<span class='text-success'>+500</span>)



Your faction standing with [Yelinak](/faction/436) got worse (<span class='text-danger'>-250</span>)



Your faction standing with [Dain Frostreaver IV](/faction/405) got worse (<span class='text-danger'>-250</span>)



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_846.png" alt="" /> <a
                                href="/item/25857" data-url="25857" class="tooltip-link link">Gauntlets of Dragon Slaying</a> (+500000 exp)

 


**This NPC *should* return incorrect items given.**

## Combat


if  King Tormax enters combat  then


**Set a timer** named *help* for 300 seconds


help_tormax(e);

else


**Stop timer** named *help*

## Timer(s)

if(e.timer == "help") then


**King Tormax shouts:** <span class="text-danger">King Tormax shouts 'Those who raise arms against me will suffer my wrath!'</span>


help_tormax(e);
end


function help_tormax(e)

local kyenka = eq.get_entity_list():GetMobByNpcTypeID(113133);



if (kyenka.valid and not kyenka:IsEngaged()) then


kyenka:CastToNPC():SetRunning(true);


kyenka:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);



local yetarr = eq.get_entity_list():GetMobByNpcTypeID(113247);



if (yetarr.valid and not yetarr:IsEngaged()) then


yetarr:CastToNPC():SetRunning(true);


yetarr:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);



local vkjen = eq.get_entity_list():GetMobByNpcTypeID(113036);



if (vkjen.valid and not vkjen:IsEngaged()) then


vkjen:CastToNPC():SetRunning(true);


vkjen:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);


local klraggek = eq.get_entity_list():GetMobByNpcTypeID(113098);



if (klraggek.valid and not klraggek:IsEngaged()) then


klraggek:CastToNPC():SetRunning(true);


klraggek:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);


local drendar = eq.get_entity_list():GetMobByNpcTypeID(113037);



if (drendar.valid and not drendar:IsEngaged()) then


drendar:CastToNPC():SetRunning(true);


drendar:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);


local irrek = eq.get_entity_list():GetMobByNpcTypeID(113302);



if (irrek.valid and not irrek:IsEngaged()) then


irrek:CastToNPC():SetRunning(true);


irrek:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);


local velden = eq.get_entity_list():GetMobByNpcTypeID(113382);



if (velden.valid and not velden:IsEngaged()) then


velden:CastToNPC():SetRunning(true);


velden:CastToNPC():MoveTo(e.self:GetX(), e.self:GetY(), e.self:GetZ(), 0, false);
end
