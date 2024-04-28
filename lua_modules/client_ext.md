# client ext
function Client:Faction(npc, faction_id, faction_value, temp)

temp = temp or 0;


if(npc:Charmed()) then


return;



self:SetFactionLevel2(self:CharacterID(), faction_id, faction_value, temp);
function Client:GiveCash(copper, silver, gold, platinum)

copper = copper or 0;

silver = silver or 0;

gold = gold or 0;

platinum = platinum or 0;



if(copper == 0 and silver == 0 and gold == 0 and platinum == 0) then


return;



self:AddMoneyToPP(copper, silver, gold, platinum, true);



local tmp = "You receive ";

local first = true;

if(platinum > 0) then


tmp = tmp .. tostring(platinum) .. " platinum";


first = false;



if(gold > 0) then


if(first) then



first = false;


else



tmp = tmp .. ", ";





tmp = tmp .. tostring(gold) .. " gold";



if(silver > 0) then


if(first) then



first = false;


else



tmp = tmp .. ", ";





tmp = tmp .. tostring(silver) .. " silver";



if(copper > 0) then


if(first) then



first = false;


else



tmp = tmp .. ", ";





tmp = tmp .. tostring(copper) .. " copper";



tmp = tmp .. " pieces.";



self:Message(260, tmp);
function Client:Ding()

self:SendSound(141);
function Client:GetFaction(npc)

return self:GetFactionLevel(self:CharacterID(), self:GetRace(), self:GetClass(), self:GetDeity(), npc:GetPrimaryFaction(), npc);
function Client:Class()

local class = self:GetClass();



do


local c = {


 [1] = "Warrior",


 [2] = "Cleric",


 [3] = "Paladin",


 [4] = "Ranger",


 [5] = "Shadowknight",


 [6] = "Druid",


 [7] = "Monk",


 [8] = "Bard",


 [9] = "Rogue",


 [10] = "Shaman",


 [11] = "Necromancer",


 [12] = "Wizard",


 [13] = "Magician",


 [14] = "Enchanter",


 [15] = "Beastlord",


 [16] = "Berserker"


 }


return c[class];
end

function Client:Race()

local race = self:GetRace();



do


local r = {


 [1] = "Human",


 [2] = "Barbarian",


 [3] = "Erudite",


 [4] = "Wood Elf",


 [5] = "High Elf",


 [6] = "Dark Elf",


 [7] = "Half Elf",


 [8] = "Dwarf",


 [9] = "Troll",


 [10] = "Ogre",


 [11] = "Halfling",


 [12] = "Gnome",


 [14] = "Werewolf",


 [74] = "Froglok",


 [75] = "Elemental",


 [108] = "Eye of Zomm",


 [120] = "Wolf Elemental",


 [128] = "Iksar",


 [130] = "Vah Shir",


 [161] = "Iksar Skeleton",


 [330] = "Froglok",


 [367] = "Skeleton",


 [522] = "Drakkin",


 ['?'] = "Unknown"


 }


return r[race];
end

function Client:HasItem(itemid)




for i = 0, 30, 1 do


local thisitem = self:GetItemIDAt(i);


if(thisitem == itemid) then



return true;





if (self:FindOnCursor(itemid)) then


return true;





for i = 250, 339, 1 do


local thisitem = self:GetItemIDAt(i);


if(thisitem == itemid) then



return true;





for i = 2000, 2007, 1 do


local thisitem = self:GetItemIDAt(i);


if(thisitem == itemid) then



return true;





for i = 2030, 2109, 1 do


local thisitem = self:GetItemIDAt(i);


if(thisitem == itemid) then



return true;






for i = 2531, 2550, 1 do


local thisitem = self:GetItemIDAt(i);


if(thisitem == itemid) then



return true;












for b = 0, bodycount, 1 do



local bodyid = self:GetCorpseID(b); 



for i = 0, 30, 1 do




local thisitem = self:GetCorpseItemAt(bodyid, i);




if(thisitem == itemid) then





return true;








for i = 250, 339, 1 do




local thisitem = self:GetCorpseItemAt(bodyid, i);




if(thisitem == itemid) then





return true;







-
return false;
function Client:ForeachHateList(func, cond)

cond = cond or function(ent, hate, damage, frenzy) return true

local lst = self:GetHateList();

for ent in lst.entries do


local cv = cond(ent.ent, ent.hate, ent.damage, ent.frenzy);


if(cv) then



func(ent.ent, ent.hate, ent.damage, ent.frenzy);

end

function Client:CountHateList(cond)

cond = cond or function(ent, hate, damage, frenzy) return true

local lst = self:GetHateList();

local ret = 0;

for ent in lst.entries do


local cv = cond(ent.ent, ent.hate, ent.damage, ent.frenzy);


if(cv) then



ret = ret + 1;




return ret;