# Imxil Tbrow
local factionId = 0;

## Dialog

**You say:** `hail`



>**Imxil Tbrow says:** I have no desire to speak with anyone. That includes you!
end

## Combat

if ( not e.joined and factionId ~= 0 ) then


e.self:CastToNPC():SetNPCFactionID(factionId);


end


## Signals

if ( e.self:IsEngaged() ) then


return;


local turn, bard;



if ( e.signal == 1 ) then














>**Imxil Tbrow says:** Go ahead and unite, fools. It will make it easier for the Teir'Dal to conquer you.


**Signaled to:**  [Plnorrick Spinecracker](/npc/10163)


elseif ( e.signal == 2 ) then


>**Imxil Tbrow says:** Those halfwit ogres make good pets. If they are housebroken.


turn = true;

elseif ( e.signal == 4 ) then


>**Imxil Tbrow says:** The Teir'Dal cower to no one. We are the only true force to be reckoned with.


turn = true;

elseif ( e.signal == 5 ) then


>**Imxil Tbrow says:** There are no greater circles of magic than those of the Teir'Dal.


turn = true;

elseif ( e.signal == 7 ) then


>**Imxil Tbrow says:** Let Sir Lucan D'Lere seek glory while we Teir'Dal seek great destiny.


turn = true;

elseif ( e.signal == 10 ) then


factionId = e.self:CastToNPC():GetNPCFactionID();


e.self:CastToNPC():SetNPCFactionID(0);






if ( turn ) then


bard = eq.get_entity_list():GetMobByNpcTypeID(10141);





if ( not bard.valid ) then



bard = eq.get_entity_list():GetMobByNpcTypeID(10158);





if ( not bard.valid ) then 



bard = eq.get_entity_list():GetMobByNpcTypeID(10165);





if ( bard.valid ) then



e.self:FaceTarget(bard);

end

## Turn-Ins



**This NPC *should* return incorrect items given.**

end