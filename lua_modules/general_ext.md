# general ext





function eq.ChooseRandom(...)

local tbl = {...};

return tbl[math.random(#tbl)];
function eq.SelfCast(spell_id)

local init = eq.get_initiator();

local sp = Spell(spell_id);



if(init.null or sp.null) then


return;



init:SpellFinished(spell_id, init, 10, 0, -1, sp:ResistDiff());
function eq.ClassType(class)

if(class == 8 or class == 15 or class == 3 or class == 4 or class == 5) then


return "hybrid";

elseif(class == 1 or class == 7 or class == 16 or class == 9) then


return "melee";

elseif(class == 11 or class == 12 or class == 13 or class == 14) then


return "caster"

elseif(class == 2 or class == 10 or class == 6) then


return "priest";



return "other";

function eq.RandomCash(min, max)

local total = math.random(min, max)

local platinum = math.modf(total / 1000)

total = total - platinum * 1000

local gold = math.modf(total / 100)

total = total - gold * 100

local silver = math.modf(total / 10)

total = total - silver * 10

return total, silver, gold, platinum