# a docile bear
local reaction = 0;



## Signals

if(e.signal == 1) then


eq.follow(eq.get_entity_list():GetMobByNpcTypeID(181164):GetID(),15);

elseif(e.signal == 2) then


eq.stop_follow();


**Set a timer** named *react* for 3 seconds
end



## Timer(s)

if(e.timer == "react") then


reaction = reaction + 1;


if(reaction == 1) then



e.self:DoAnim(12);


elseif(reaction == 2) then



e.self:DoAnim(12);


elseif(reaction == 3) then



e.self:DoAnim(12);


elseif(reaction == 4) then



e.self:DoAnim(12);



**Stop timer** named *react*



**Spawn NPC:**  [a defiled bear](/npc/181015) at this location.



**a docile bear despawns.**

end
