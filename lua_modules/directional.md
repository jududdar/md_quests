# directional
function Mob:DirectionalAreaEffectList(angle_start, angle_end, aoe_range, min_range, m_list)


angle_start = angle_start + (self:GetHeading() * 360.0 / 256.0);

angle_end = angle_end + (self:GetHeading() * 360.0 / 256.0);



while(angle_start > 360.0) do


angle_start = angle_start - 360.0;



while(angle_end > 360.0) do


angle_end = angle_end - 360.0;


local ret = { };

for ent in m_list.entries do


if(ent:GetID() ~= self:GetID()) then



local x_diff = ent:GetX() - self:GetX();



x_diff = x_diff * x_diff;







local y_diff = ent:GetY() - self:GetY();



y_diff = y_diff * y_diff;







local z_diff = ent:GetZ() - self:GetZ();



z_diff = z_diff * z_diff;







if(((x_diff + y_diff) <= (aoe_range * aoe_range)) and (z_diff <= ((aoe_range * aoe_range) / 2))) then




local heading_to_target = self:CalculateHeadingToTarget(ent:GetX(), ent:GetY()) * 360.0 / 256.0;




while(heading_to_target < 0.0) do





heading_to_target = heading_to_target + 360.0;












while(heading_to_target > 360.0) do





heading_to_target = heading_to_target - 360.0;












if(angle_start > angle_end) then





if((heading_to_target >= angle_start and heading_to_target <= 360.0) or (heading_to_target >= 0.0 and heading_to_target <= angle_end)) then






table.insert(ret, ent);








else





if(heading_to_target >= angle_start and heading_to_target <= angle_end) then






table.insert(ret, ent);













return ret;
function NPC:DirectionalAreaEffectList(angle_start, angle_end, aoe_range, min_range, m_list)


angle_start = angle_start + (self:GetHeading() * 360.0 / 256.0);

angle_end = angle_end + (self:GetHeading() * 360.0 / 256.0);



while(angle_start > 360.0) do


angle_start = angle_start - 360.0;



while(angle_end > 360.0) do


angle_end = angle_end - 360.0;


local ret = { };

for ent in m_list.entries do


if(ent:GetID() ~= self:GetID()) then



local x_diff = ent:GetX() - self:GetX();



x_diff = x_diff * x_diff;







local y_diff = ent:GetY() - self:GetY();



y_diff = y_diff * y_diff;







local z_diff = ent:GetZ() - self:GetZ();



z_diff = z_diff * z_diff;







if(((x_diff + y_diff) <= (aoe_range * aoe_range)) and (z_diff <= ((aoe_range * aoe_range) / 2))) then




local heading_to_target = self:CalculateHeadingToTarget(ent:GetX(), ent:GetY()) * 360.0 / 256.0;




while(heading_to_target < 0.0) do





heading_to_target = heading_to_target + 360.0;












while(heading_to_target > 360.0) do





heading_to_target = heading_to_target - 360.0;












if(angle_start > angle_end) then





if((heading_to_target >= angle_start and heading_to_target <= 360.0) or (heading_to_target >= 0.0 and heading_to_target <= angle_end)) then






table.insert(ret, ent);








else





if(heading_to_target >= angle_start and heading_to_target <= angle_end) then






table.insert(ret, ent);













return ret;
function Client:DirectionalAreaEffectList(angle_start, angle_end, aoe_range, min_range, m_list)


angle_start = angle_start + (self:GetHeading() * 360.0 / 256.0);

angle_end = angle_end + (self:GetHeading() * 360.0 / 256.0);



while(angle_start > 360.0) do


angle_start = angle_start - 360.0;



while(angle_end > 360.0) do


angle_end = angle_end - 360.0;


local ret = { };

for ent in m_list.entries do


if(ent:GetID() ~= self:GetID()) then



local x_diff = ent:GetX() - self:GetX();



x_diff = x_diff * x_diff;







local y_diff = ent:GetY() - self:GetY();



y_diff = y_diff * y_diff;







local z_diff = ent:GetZ() - self:GetZ();



z_diff = z_diff * z_diff;







if(((x_diff + y_diff) <= (aoe_range * aoe_range)) and (z_diff <= ((aoe_range * aoe_range) / 2))) then




local heading_to_target = self:CalculateHeadingToTarget(ent:GetX(), ent:GetY()) * 360.0 / 256.0;




while(heading_to_target < 0.0) do





heading_to_target = heading_to_target + 360.0;












while(heading_to_target > 360.0) do





heading_to_target = heading_to_target - 360.0;












if(angle_start > angle_end) then





if((heading_to_target >= angle_start and heading_to_target <= 360.0) or (heading_to_target >= 0.0 and heading_to_target <= angle_end)) then






table.insert(ret, ent);








else





if(heading_to_target >= angle_start and heading_to_target <= angle_end) then






table.insert(ret, ent);













return ret;
end