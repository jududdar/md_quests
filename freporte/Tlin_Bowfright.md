# Tlin Bowfright


## Dialog

**You say:** `hail`



>**Tlin Bowfright says:** Nice to meet you! Sit down! Have some food and grog. Just learn not to annoy anyone in here. This place attracts a pretty rough crowd at times. It is not uncommon to have a brawl break out
end



## Signals

if ( e.self:IsEngaged() ) then


return;


local turn, bard;



if ( e.signal == 1 ) then


>**Tlin Bowfright says:** Let's all live together in peace. That is, everyone except the ogres, trolls and dark elves!


turn = true;

elseif ( e.signal == 2 ) then


>**Tlin Bowfright says:** Yes. Those ogres sure are dumb and smelly.


turn = true;

elseif ( e.signal == 4 ) then


>**Tlin Bowfright says:** I wish the Qeynos Guards would come and conquer Freeport. The Freeport Militia are nothing more than mercenaries and criminals.


turn = true;

elseif ( e.signal == 6 ) then


>**Tlin Bowfright says:** I shall take care of you, milady.


turn = true;

elseif ( e.signal == 7 ) then


>**Tlin Bowfright says:** Hey!! Keep it down! The Freeport Militia might hear that song and arrest us all.


turn = true;

elseif ( e.signal == 10 ) then


>**Tlin Bowfright says:** The only blithering fool in here is you, Talym Shoontar.


**Signaled to:**  [Talym Shoontar](/npc/10182)



if ( turn ) then


bard = eq.get_entity_list():GetMobByNpcTypeID(10141);





if ( not bard.valid ) then



bard = eq.get_entity_list():GetMobByNpcTypeID(10158);





if ( not bard.valid ) then 



bard = eq.get_entity_list():GetMobByNpcTypeID(10165);





if ( bard.valid ) then



e.self:FaceTarget(bard);

end
