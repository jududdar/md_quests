# Tubal Weaver


## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>**Tubal Weaver says:** Hey!  Someone dropped a perfectly good thing-a-ma-jig!  Oh well, finders keepers!




## Dialog

**You say:** `hail`



>**Tubal Weaver says:** Hail, Soandso!  I am Tubal Weaver, humble merchant and retired guardsman of Highkeep.  I make a tidy living dealing with the throngs of adventurers who take it upon themselves to keep Qeynos beetle-free.  If you want some free advice, I recommend that you not deal with any of the merchants in town.  I can offer much lower prices than they because I do not have the overhead of a shop to maintain.
end



## Arrive at Waypoint Script

if(e.wp == 2) then


>**Tubal Weaver says:** Whew. I am parched. I will be back in a few minutes.


e.self:MerchantCloseShop();

elseif(e.wp == 15) then


>**Tubal Weaver says:** Hey sweetheart, I'll have my usual. Could you bring it upstairs for me?


**Signaled to:**  [Sabnie Blagard](/npc/2083)

elseif(e.wp == 38) then


>**Tubal Weaver says:** Hey, hey, hey! Tubal Weaver open for business!


e.self:MerchantOpenShop();
end



## Signals

local xloc = e.self:GetX();

local yloc = e.self:GetY();



if(e.signal == 1 and xloc == 372 and yloc == 37) then


>**Tubal Weaver says:** Is he wise to us?


**Signaled to:**  [Sabnie Blagard](/npc/2083)

elseif(e.signal == 2) then


>**Tubal Weaver says:** Well, we won't have to worry about him much longer. I have some friends coming into town who owe me the kind of debt you can't repay with gold.


**Signaled to:**  [Sabnie Blagard](/npc/2083)

elseif(e.signal == 3) then


>**Tubal Weaver says:** Don't you worry, sugar, his days are numbered. You better get back before he suspects something. We'll be together soon enough.
end
