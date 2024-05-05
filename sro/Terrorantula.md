# Terrorantula



[Terrorantula](/npc/35144) is a level 37 Spider Warrior that spawns in [Southern Desert of Ro](/zone/35).





## On NPC Death

xloc = e.self:GetX();

yloc = e.self:GetY();

zloc = e.self:GetZ();

myheading = e.self:GetHeading();

eq.spawn2(35069,15,0,xloc + 5,yloc,zloc,myheading); 

eq.spawn2(35069,15,0,xloc - 5,yloc,zloc,myheading); 

eq.spawn2(35069,15,0,xloc,yloc + 5,zloc,myheading); 

eq.spawn2(35069,15,0,xloc,yloc - 5,zloc,myheading); 