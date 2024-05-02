# Shainai
## On NPC Spawn

eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(150);
## Arrive at Waypoint Script

if(e.wp == 17) then


>*Shainai stops skipping and looks around, 'Uh oh'*

elseif(e.wp == 43) then


>*Shainai glances about, looking a bit lost. 'Well this doesn't look like a place I belong in at all'*

elseif(e.wp == 49) then


>**Shainai says:** Uh oh? this looks dangerous, I don't think I am allowed to be here.

elseif(e.wp == 51) then


>*Shainai notices the pile of bones next to her and shudders, 'Eeep! I wonder what happened to him.*

elseif(e.wp == 57) then


>**Shainai says:** Hi, how do I get outside, huh?

elseif(e.wp == 58) then


>*Shainai smiles at the sight of daylight, 'Ahhh yes, this is the way!'*

elseif(e.wp == 66) then


>*Shainai squints around, thinking hard, 'Hrmmm, this does look familiar. I think i came from this-a-way.'*

elseif(e.wp == 68) then


>**Shainai says:** Oh look, there it is!

elseif(e.wp == 80) then


>*Shainai Yawns tiredly and says, 'That was fun. Time for me to go to sleep though.' She crawls under the blanket and falls sound asleep.*
end

## Dialog

local a = 155339;

**You say:** `hail`



if(e.self:GetWaypointID() < 17) then



>**Shainai says:** Hello, my name is Shainai and I am on a very important mission for my Daddy. He ran out of buttons for the officers' clothes so I have to get him more. I am an excellent helper.


elseif(e.self:GetWaypointID() > 16 and e.self:GetWaypointID() < 59) then



>**Shainai says:** Hi. I was getting some buttons for Daddy and I got a little lost. I know the way, I mean it...but if you wanted to [follow] me home to make sure I got there safe and all, you could.


elseif(e.self:GetWaypointID() > 58) then



>**Shainai says:** Hi there, I am headed home before I get in trouble.  I got a little lost, but I am ok now.  I hope Daddy isn't too mad.  Bye bye!


**You say:** `follow`



if(e.self:GetWaypointID() > 16 and e.self:GetWaypointID() < 59) then



>**Shainai says:** You will?!? Oh good, now I won't be so lonesome. Here hold my bag of buttons if you please, my arms are tired. Ready? Follow me now, I know the way.  'Shainai pauses and looks around, ' Hmmmm...



 &#127873; **You receive:**  <img style="background:url(/static/icons/blank_slot.gif);width:20px;height:20px;" src="/static/icons/item_691.png" alt="" /> <a
                                href="/item/4460" data-url="4460" class="tooltip-link link">Shainais Bag</a> 

 



if(e.self:GetWaypointID() > 16 and e.self:GetWaypointID() < 21) then



eq.unique_spawn(a,31,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 20 and e.self:GetWaypointID() < 24) then



eq.unique_spawn(a,32,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 23 and e.self:GetWaypointID() < 26) then



eq.unique_spawn(a,33,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 25 and e.self:GetWaypointID() < 28) then



eq.unique_spawn(a,29,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 27 and e.self:GetWaypointID() < 32) then



eq.unique_spawn(a,27,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 31 and e.self:GetWaypointID() < 36) then



eq.unique_spawn(a,34,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 35 and e.self:GetWaypointID() < 38) then



eq.unique_spawn(a,28,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 37 and e.self:GetWaypointID() < 45) then



eq.unique_spawn(a,30,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 44 and e.self:GetWaypointID() < 48) then



eq.unique_spawn(a,35,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**


elseif(e.self:GetWaypointID() > 47 and e.self:GetWaypointID() < 59) then



eq.unique_spawn(a,36,0,e.self:GetX(),e.self:GetY(),e.self:GetZ(),e.self:GetHeading());



eq.get_entity_list():GetSpawnByID(e.self:GetSpawnPointID()):SetRespawnTimer(1800);



**Shainai despawns.**

end

## Turn-Ins



**This NPC *should* return incorrect items given.**
