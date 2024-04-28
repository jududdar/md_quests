# Rumbleroot
## Combat

if Rumbleroot enters combat  then


call_zone_to_assist(e.self,e.other);


**Set a timer** named *come* for 300 seconds

else


**Stop timer** named *come*
end

## Timer(s)

if(e.timer == "come") then


**Rumbleroot shouts:** <span class="text-danger">Spirits of the groves, you are needed now!</span>


call_zone_to_assist(e.self,e.other);
end

function call_zone_to_assist(e_self,e_other)



local show_debug = false;



local entity_list = eq.get_entity_list();



local include_npc_list = Set {127025,127108}; 

local npc_list = entity_list:GetNPCList();

if (npc_list ~= nil) then


for npc in npc_list.entries do



if (include_npc_list[npc:GetNPCTypeID()] ~= nil) then









if (npc.valid) then





npc:CastToNPC():MoveTo(e_self:GetX(),e_self:GetY(),e_self:GetZ(),0,false);





if (show_debug) then e_other:Message(4,"NPCID: " .. npc:GetNPCTypeID() .. " is valid, adding hate on " .. npc:GetName() .. ".");



else





if (show_debug) then e_other:Message(4,"NPCID: " .. npc:GetNPCTypeID() .. " is invalid, unable to add hate on " .. npc:GetName() .. ".");





else




if (show_debug) then e_other:Message(4,"NPCID: " .. npc:GetNPCTypeID() .. " is excluded, not adding hate on " .. npc:GetName() .. ".");


end



function Set (list)
  local set = {}
  for _, l in ipairs(list) do set[l] = true  return set