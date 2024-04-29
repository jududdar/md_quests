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







if( **You turn in:** [Dain Frostreaver's Head](/item/30501)) then 


if( **Faction is** > Threatening) then



* __Faction:__ [King Tormax](/faction/429) (500)



* __Faction:__ [Kromzek](/faction/448) (500)



* __Faction:__ [Yelinak](/faction/436) (-250)



* __Faction:__ [Dain Frostreaver IV](/faction/405) (-250)



 **You receive:**  [Belt of Dwarf Slaying](/item/25858) (+500000 exp)


elseif( **You turn in:** [Yelinak's Head](/item/24984)) then 


if( **Faction is** > Threatening) then



* __Faction:__ [King Tormax](/faction/429) (500)



* __Faction:__ [Kromzek](/faction/448) (500)



* __Faction:__ [Yelinak](/faction/436) (-250)



* __Faction:__ [Dain Frostreaver IV](/faction/405) (-250)



 **You receive:**  [Gauntlets of Dragon Slaying](/item/25857) (+500000 exp)


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
