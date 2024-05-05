# Barthal



[Barthal](/npc/1115) is a level 37 Human Shopkeeper that spawns in [South Qeynos](/zone/1).



## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Barthal picks up a discarded item from the ground and says, 'Don't people have enough respect for our grand city to not throw things onto the streets?!*




## Dialog

**You say:** `hail`



>**Barthal says:** Hail, Soandso! We've got the best prices in town..  No need to shop around..  Heh, heh. I think I'll make that my new slogan!

**You say:** `donate`



>**Barthal says:** Please do not request donations or handouts. I have no extra money. If I did I would rent a shop.







end



## Signals

if(e.signal == 1) then


eq.stop();


e.self:MerchantCloseShop();

elseif(e.signal == 2) then


eq.start(61);


e.self:MerchantOpenShop();

elseif(e.signal == 3) then


>**Barthal says:** Heh.. Why don't you try Freeport.. or Erudin.. ANYwhere but here!
end
