# Moran Smith



[Moran Smith](/npc/1078) is a level 45 Human Shopkeeper that spawns in [South Qeynos](/zone/1).



## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds

e.self:SetRunning(true);


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Moran Smith picks up a discarded item from the ground and says, 'Don't people have enough respect for our grand city to not throw things onto the streets?!*




## Signals

if(e.signal == 1) then


eq.stop();


e.self:MerchantCloseShop();

elseif(e.signal == 2) then


eq.start(60);


e.self:MerchantOpenShop();
end



## Dialog

**You say:** `hail`



>**Moran Smith says:** Greetings!! Moran here. I just love this city. I traveled from Freeport to Qeynos to stay far from the [Freeport Militia].

**You say:** `freeport militia`



>**Moran Smith says:** The Freeport Militia are nothing more than thugs. I have seen them lay waste to more than a dozen adventurers at once. For no reason other than to flex their muscles!

**You say:** `kane`



>**Moran Smith says:** Commander Kane Bayle is the commander of all the Qeynos Guard.  He is second only to his brother, Antonius Bayle.  His post is in the guard house at the city gates.  Mind you, do not bother him, he has a bit of a temper.



**You say:** `circle.* unseen hand`



>**Moran Smith says:** The Circle of the Unseen Hand?  I have heard nothing of them.  Are they some sort of performing magic troupe?


**You say:** `donate`



>**Moran Smith says:** I am sorry. I have no extra currency to donate.




end
