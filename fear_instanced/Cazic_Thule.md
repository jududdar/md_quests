# Cazic Thule



[Cazic Thule](/npc/72003) is a level 70 Cazic Thule Shadow Knight that spawns in [Plane of Fear (Instanced)](/zone/1072).





## On NPC Spawn

**Set a timer** named *Shout* for 600 seconds






## Dialog

**You say:** `gandan has failed in his task`



>*Cazic Thule 's thoughts begin to pervade your own, they creep into your mind with great force. You feel pressure as if your head will explode. You see his thoughts becoming your own. You see in these visions a tome bound in flesh dropped to the ground. You then open your eyes to see that same book, and take it knowing that it was meant for you.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18898" data-url="18898" class="tooltip-link link">Flayed Skin Tome</a>
end



## Turn-Ins



if( **You turn in:** <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18898" data-url="18898" class="tooltip-link link">Flayed Skin Tome</a>, <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_778.png" alt="" /> <a
                                href="/item/18899" data-url="18899" class="tooltip-link link">Flayed Skin Tome</a>) then


>*Cazic Thule seems pleased with the amount of pain that you have been able to inflict. Cazic Thule then grabs your hands and begins to infuse them with his power. Your hands burn like they were placed in lava for a moment, then feel cool as ice. You can feel the sheer power flowing through your new weapons of pain.*


 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_971.png" alt="" /> <a
                                href="/item/7836" data-url="7836" class="tooltip-link link">Whistling Fists</a> (+100000 exp)

 

**This NPC *should* return incorrect items given.**



## Combat

if  Cazic Thule enters combat  then





**Cazic Thule shouts:** <span class="text-danger">Denizens of Fear, your master commands you to come forth to his aid!!</span>


call_zone_to_assist(e.self,e.other);


**Stop timer** named *Shout*


**Set a timer** named *come* for 300 seconds

else


**Stop timer** named *come*


**Set a timer** named *Shout* for 600 seconds
end



## Timer(s)

if(e.timer == "Shout" and eq.get_entity_list():GetClientList() ~= nil) then


**Cazic Thule shouts:** <span class="text-danger">Beware all infidels who dare to taint my plane, for I shall rend your minds with fright, dread, and terror!</span>








send_signal_to_all_npc_in_zone(1, {72078,72074,72012});

elseif(e.timer == "come") then


**Cazic Thule shouts:** <span class="text-danger">Denizens of Fear, your master commands you to come forth to his aid!!</span>


call_zone_to_assist(e.self,e.other);

elseif(e.timer == "RepopZone") then


**Stop timer** named *RepopZone*
end



## On NPC Death

**Stop timer** named *come*
function call_zone_to_assist(e_self,e_other)



local show_debug = false;



local entity_list = eq.get_entity_list();





local exclude_npc_list = Set {72078,72074,72012};

local npc_list = entity_list:GetNPCList();

if (npc_list ~= nil) then


for npc in npc_list.entries do



if (exclude_npc_list[npc:GetNPCTypeID()] == nil) then









if (npc.valid) then





if(npc:GetNPCTypeID() == 72000 or npc:GetNPCTypeID() == 72004 or npc:GetNPCTypeID() == 72002 or npc:GetNPCTypeID() == 72090 or 





npc:GetNPCTypeID() == 72590 or npc:GetNPCTypeID() == 72600 or npc:GetNPCTypeID() == 72601 or npc:GetNPCTypeID() == 72602 or





npc:GetNPCTypeID() == 72604 or npc:GetNPCTypeID() == 72690) then






npc:CastToNPC():GMMove(e_self:GetX(),e_self:GetY(),e_self:GetZ(),0,true);






npc:CastToNPC():SaveGuardSpot();





else






npc:CastToNPC():MoveTo(e_self:GetX(),e_self:GetY(),e_self:GetZ(),0,false);









if (show_debug) then e_other:Message(4,"NPCID: " .. npc:GetNPCTypeID() .. " is valid, adding hate on " .. npc:GetName() .. ".");



else





if (show_debug) then e_other:Message(4,"NPCID: " .. npc:GetNPCTypeID() .. " is invalid, unable to add hate on " .. npc:GetName() .. ".");





else




if (show_debug) then e_other:Message(4,"NPCID: " .. npc:GetNPCTypeID() .. " is excluded, not adding hate on " .. npc:GetName() .. ".");


end

function send_signal_to_all_npc_in_zone(signal_to_send,exclude_table)



local show_debug = false;



local exclude_npc_list = Set(exclude_table);



local signal_sent_to = {};



local entity_list = eq.get_entity_list();



local npc_list = entity_list:GetNPCList();



if(npc_list ~= nil) then


for npc in npc_list.entries do



if (exclude_npc_list[npc:GetNPCTypeID()] == nil and signal_sent_to[npc:GetNPCTypeID()] == nil) then









if (npc.valid) then





if (show_debug) then **Zone Wide Emote:** <span class="text-warning">*NPCID: " .. npc:GetNPCTypeID() .. " is being sent signal " .. tostring(signal_to_send) .. ".*</span>










eq.signal(npc:GetNPCTypeID(),signal_to_send);











signal_sent_to[npc:GetNPCTypeID()] = true;






elseif(signal_sent_to[npc:GetNPCTypeID()] == true) then




if (show_debug) then **Zone Wide Emote:** <span class="text-warning">*NPCID: " .. npc:GetNPCTypeID() .. " has already been sent signal " .. tostring(signal_to_send) .. ".*</span>


elseif(exclude_npc_list[npc:GetNPCTypeID()] == true) then




if (show_debug) then **Zone Wide Emote:** <span class="text-warning">*NPCID: " .. npc:GetNPCTypeID() .. " is excluded and will not be sent signal " .. tostring(signal_to_send) .. ".*</span>


end



function Set (list)
  local set = {}
  for _, l in ipairs(list) do set[l] = true  return set