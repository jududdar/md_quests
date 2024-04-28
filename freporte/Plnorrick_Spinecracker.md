# Plnorrick Spinecracker
## Dialog

**You say:** `hail`



>**Plnorrick Spinecracker says:** What do you want? I don't have any spare change.
end

## Signals

if ( e.self:IsEngaged() ) then


return;


local turn, bard;



if ( e.signal == 1 ) then


>**Plnorrick Spinecracker says:** Yes. We shall live together. We shall be strong.


turn = true;

elseif ( e.signal == 2 ) then


>**Plnorrick Spinecracker says:** Ha!! Dumb ogres. Plnorrick can bash any of them.


turn = true;

elseif ( e.signal == 3 ) then


>**Plnorrick Spinecracker says:** <Clap>.. <Clap>.. <Glug, glug>.. Ahh. I love that song. <Hic!!>


turn = true;



elseif ( e.signal == 5 ) then


>**Plnorrick Spinecracker says:** Smash Erudin!! They are weak. They should be destroyed!!


turn = true;

elseif ( e.signal == 10 ) then














>**Plnorrick Spinecracker says:** My fist will unite with your face.


e.self:AddToHateList(eq.get_entity_list():GetMobByNpcTypeID( [Imxil Tbrow](/npc/10012)),500); 


**Signaled to:**  [Imxil Tbrow](/npc/10012)



if ( turn ) then


bard = eq.get_entity_list():GetMobByNpcTypeID(10141);





if ( not bard.valid ) then



bard = eq.get_entity_list():GetMobByNpcTypeID(10158);





if ( not bard.valid ) then 



bard = eq.get_entity_list():GetMobByNpcTypeID(10165);





if ( bard.valid ) then



e.self:FaceTarget(bard);

end
