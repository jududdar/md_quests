# Cleet Miller Jr



[Cleet Miller Jr](/npc/12029) is a level 6 Human Shopkeeper that spawns in [Western Plains of Karana](/zone/12).



## Dialog

**You say:** `hail`



>*Cleet Miller Jr grumbles and looks up at you.*

**You say:** `who`



e.self:Say(string.format("Listen, %s, I don't want to be rude, but these fields don't tend to themselves, you know.  I don't have time for your little questions.  Go talk to Tiny if you are feeling chatty.",e.other:GetName()));





end



## Arrive at Waypoint Script

local xloc = e.self:GetX();

local yloc = e.self:GetY();

local zloc = e.self:GetZ();



if(e.wp == 2 or e.wp == 9) then


>*Cleet Miller Jr gathers up a bale of straw*


eq.create_ground_object(13990,xloc,yloc,zloc,0,600000);

elseif(e.wp == 3 or e.wp == 10) then


e.self:SetRunning(true);

elseif(e.wp == 5 or e.wp == 12) then


e.self:SetRunning(false);
end
