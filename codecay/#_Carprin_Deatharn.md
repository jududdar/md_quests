#  Carprin Deatharn
## Combat

if   Carprin Deatharn enters combat  then


local mob1 = **Spawn NPC:**  [\#Breddan Rutyl](/npc/200229) at (**y:** -127, **x:** 382)


local mob2 = **Spawn NPC:**  [\#Fran Prisoal](/npc/200230) at (**y:** -108, **x:** 364)


local mob3 = **Spawn NPC:**  [\#Abroan Drian](/npc/200222) at (**y:** -94, **x:** 384)


**Set a timer** named *drophate* for 1 seconds


if ( math.abs(e.self:GetX() - e.self:GetSpawnPointX()) < 1 and math.abs(e.self:GetY() - e.self:GetSpawnPointY()) < 1 ) then



eq.get_entity_list():MessageClose(e.self, true, 200, 0, "The dark knight looks at the foolish mortals who have come into his domain and begins to chant a dark spell, 'Doremai Peyunai Rezgra Yru Zainweedi QUANDOZI QUANDOZI QUANDOZI!'  Suddenly, three howls of pain and agony are heard as the foul knight channels energy from the tortured souls surrounding him.  He grins evilly as a shimmering field of dark force surrounds him powered by the stolen energy and says, 'I shall enslave your souls for all eternity and you will learn what it means to defy my lord, Bertoxxulous.'");



if ( mob1.valid ) then mob1:AddToHateList(e.other, 1);


if ( mob2.valid ) then mob2:AddToHateList(e.other, 1);


if ( mob3.valid ) then mob3:AddToHateList(e.other, 1);



else


**Stop timer** named *drophate*

















local ratio = e.self:GetHPRatio();


if ( ratio < 50 or math.random(100) > ratio ) then



e.self:GMMove(e.self:GetGuardPointX(), e.self:GetGuardPointY(), e.self:GetGuardPointZ(), e.self:GetSpawnPointH());



e.self:SetHP(e.self:GetHP() + math.floor(e.self:GetMaxHP() * 0.3));

end

## Timer(s)


if ( e.timer == "drophate") then




if ( math.random() < 0.01666 ) then 



local target = e.self:GetTarget();



if ( target and target.valid ) then




e.self:RemoveFromHateList(target);





eq.debug(e.self:GetName().." dropped target from hate list ("..target:GetName()..")", 2);

end