# Lord Inquisitor Seru
local SpawnX = 0;
local SpawnY = 0;
local SpawnZ = 0;
local SpawnH = 0;



## On NPC Spawn

SpawnX = e.self:GetX();

SpawnY = e.self:GetY();

SpawnZ = e.self:GetZ();

SpawnH = e.self:GetHeading();



e.self:SetSkill(11, 250);




## Combat

if Lord Inquisitor Seru enters combat  then


**Set a timer** named *goback* for 1 seconds

else


**Stop timer** named *goback*


e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);
end



## Timer(s)

if(e.timer == "goback") then


if(e.self:GetX() < -364 or e.self:GetX() > -100 or e.self:GetY() < -564 or e.self:GetY() > -300) then



**Lord Inquisitor Seru shouts:** <span class="text-danger">No! I must not leave the time chamber! If I do, I'll age and die!</span>



e.self:GMMove(SpawnX,SpawnY,SpawnZ,SpawnH);



e.self:BuffFadeAll();



**Lord Inquisitor Seru** clears hate list.



e.self:Heal();

end
