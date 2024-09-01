local module = {}

function module.check_dialog(self, other, message)
local is_self_found = other:IsSelfFound() == 1 or other:IsSoloOnly() == 1;
local is_warrior = other:GetClass() == 1;
if(is_self_found) then
if(message:findi("rebreather")) then
if (is_warrior and other:GetLevel() >= 46) then
self:Say("Rebreathers are what you seek? Ha!! Extras have I and trade can we make. I call for Platinum.. 5750 Platinum Coins!! This the trade that I call.");
else
self:Say("Rebreathers are what you seek? Ha!! Extras have I but you are too weak!!");


return true;



return false;


function module.check_turn_in(item_lib, self, other, trade)
local is_self_found = other:IsSelfFound() == 1 or other:IsSoloOnly() == 1;
local is_warrior = other:GetClass() == 1;
if(is_self_found) then
if (is_warrior and other:GetLevel() >= 46) then
if( **You turn in:** platinum = 5750) then
self:Say("The time to trade has come!! I am now rich and you are now poor. Take this rebreather and swim in the deep.");
other:QuestReward(self,0,0,0,0,16889);

return true;




return false;


return module;