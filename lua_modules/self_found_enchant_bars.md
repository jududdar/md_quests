local enchant_bars = {}

function enchant_bars._check_bar_type(item_lib, self, other, trade, bar_data)
local num_bars = 0;
local required_level = bar_data.required_level;
local bar_id = bar_data.bar_id;
local reward_id = bar_data.reward_id;
local plat_cost = bar_data.plat_cost;

if (other:GetLevel() >= required_level) then

if( **You turn in:** item1 = bar_id, item2 = bar_id, item3 = bar_id, item4 = bar_id, platinum = plat_cost * 4) then
num_bars = 4;
elseif( **You turn in:** item1 = bar_id, item2 = bar_id, item3 = bar_id, platinum = plat_cost * 3) then
num_bars = 3;
elseif( **You turn in:** item1 = bar_id, item2 = bar_id, platinum = plat_cost * 2) then
num_bars = 2;
elseif( **You turn in:** item1 = bar_id, platinum = plat_cost) then
num_bars = 1;


if(num_bars > 0) then
repeat
other:SummonCursorItem(reward_id, 1); 
num_bars = num_bars - 1;
until num_bars == 0
self:Say("Your metal has been successfully imbued with the mystical energies you seek. Behold, its transformation is complete. May this enchanted metal serve as a testament to your growing intellect and mastery over the arcane. Use it with keen insight on your journey.");
self:CastSpell(667,self:GetID()); 




function enchant_bars._get_bar_data()
return {
{

bar_name = "silver",
component_name = "Silver Bar",
bar_id = 16500,
reward_id = 16504,
plat_cost = 5,
required_level = 8
},
{

bar_name = "electrum",
component_name = "Electrum Bar",
required_level = 16,
bar_id = 16501,
reward_id = 16505,
plat_cost = 10,
},
{

bar_name = "gold",
component_name = "Gold Bar",
required_level = 20,
bar_id = 16502,
reward_id = 16506,
plat_cost = 25,
},
{

bar_name = "platinum",
component_name = "Platinum Bar",
required_level = 24,
bar_id = 16503,
reward_id = 16507,
plat_cost = 50,
},
{

bar_name = "velium",
component_name = "Velium Bar",
required_level = 44,
bar_id = 22098,
reward_id = 22099,
plat_cost = 125,
},
{

bar_name = "clay",
component_name = "Large Block of Clay",
required_level = 8,
bar_id = 16902,
reward_id = 16896,
plat_cost = 5,
},
{

bar_name = "mithril",
component_name = "Large Brick of Mithril",
required_level = 20,
bar_id = 10476,
reward_id = 10455,
plat_cost = 50,
},
{

bar_name = "adamantite",
component_name = "Large Brick of Adamantite",
required_level = 20,
bar_id = 10475,
reward_id = 10449,
plat_cost = 60,
},
{

bar_name = "steel",
component_name = "Large Brick of High Quality Ore",
required_level = 20,
bar_id = 10469,
reward_id = 10440,
plat_cost = 30,
},
{

bar_name = "brellium",
component_name = "Large Brick of Brellium",
required_level = 20,
bar_id = 10474,
reward_id = 10434,
plat_cost = 30,
},
};


function enchant_bars.check_bars_quest_dialogue(self, other, message)

local is_self_found = other:IsSelfFound() == 1 or other:IsSoloOnly() == 1;
if(is_self_found) then

local bar_data_list = enchant_bars._get_bar_data();


for index, bar_data in ipairs(bar_data_list) do
enchant_bars.check_bar_quest_dialogue(self, other, message, bar_data);


if(message:findi("Hail")) then
self:Say("Are you in need of [enchantments]? If so, I may be able to help you.");
elseif(message:findi("enchantments")) then
self:Say("You wish to explore the deeper mysteries of metallurgy and magic? A noble path. The enchantment of metal is a delicate art. I can enchant [silver], [electrum], [gold], [platinum], [velium], [clay], [mithril], [adamantite], [steel], and [brellium]. Which do you seek?");





function enchant_bars.check_bar_quest_dialogue(self, other, message, bar_data)
if(message:findi(bar_data.bar_name) and not message:findi("Hail")) then
if (other:GetLevel() >= bar_data.required_level) then
message = "Present me with " .. bar_data.plat_cost ..
" platinum pieces and your " .. bar_data.component_name ..
", and we shall begin the process of its transformation.";
self:Say(message);
else
self:Say("You are a bit too inexperienced to be dabbling in such magic, aren't you?");




function enchant_bars.check_for_bars_to_enchant(item_lib, self, other, trade)

local is_self_found = other:IsSelfFound() == 1 or other:IsSoloOnly() == 1;

local bar_data_list = enchant_bars._get_bar_data();

if(is_self_found) then

for index, bar_data in ipairs(bar_data_list) do
enchant_bars._check_bar_type(item_lib, self, other, trade, bar_data);




return enchant_bars;