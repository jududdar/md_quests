# Sabnie Blagard
## Dialog


**You say:** `hail`



>**Sabnie Blagard says:** Greetings. thirsty traveler!  I recommend trying Crow's special brew.  It's the brew that put Qeynos on the map!

## Arrive at Waypoint Script


if(e.wp == 10) then


>**Sabnie Blagard says:** Did someone order an ale up here?


**Signaled to:**  [Tubal Weaver](/npc/2062)

elseif(e.wp == 18) then


>**Sabnie Blagard says:** Tubal doesn't suspect a thing.. the poor sap.


**Signaled to:**  [Crow](/npc/2063)


## Signals


local xloc = e.self:GetX();

local yloc = e.self:GetY();


if(e.signal == 1 and xloc == 368 and yloc == 82) then


>**Sabnie Blagard says:** Um, sure. Be right.. um.. up.


**Signaled to:**  [Crow](/npc/2063)

elseif(e.signal == 2) then


>**Sabnie Blagard says:** Yes. Fine. That guy just gives me the creeps is all.


**Signaled to:**  [Crow](/npc/2063)

elseif(e.signal == 3) then


>**Sabnie Blagard says:** No. No. He is clueless. I've missed you so.


**Signaled to:**  [Tubal Weaver](/npc/2062)

elseif(e.signal == 4) then


>**Sabnie Blagard says:** Please be careful. I don't know what I would do if anything happened to you.


**Signaled to:**  [Tubal Weaver](/npc/2062)

elseif(e.signal == 5) then


>**Sabnie Blagard says:** No! um.. no. That's ok. He's just a little weird, that's all. Nothing to worry about.


**Signaled to:**  [Crow](/npc/2063)

elseif(e.signal == 6) then


>**Sabnie Blagard says:** Hee hee hee! Oh.. how sad! HEE HEE HEE HEE HEE!
