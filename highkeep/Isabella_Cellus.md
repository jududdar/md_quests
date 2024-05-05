# Isabella Cellus



[Isabella Cellus](/npc/4096) is a level 39 Human Warrior that spawns in [High Keep](/zone/6).



## Dialog

**You say:** `hail`



e.self:Say(string.format("Hello. How nice to meet you. %s!",e.other:GetName()));
end



## Arrive at Waypoint Script

if(e.wp == 8) then


>**Isabella Cellus says:** Would you please leave me alone?!

elseif(e.wp == 9) then


>**Isabella Cellus says:** I need to get out of here.

elseif(e.wp == 12) then


>**Isabella Cellus says:** Would you please stop following me!!

elseif(e.wp == 16) then


>**Isabella Cellus says:** I just adore this place.
end
