# Bassanio Weekin



[Bassanio Weekin](/npc/1095) is a level 45 Human Shopkeeper that spawns in [South Qeynos](/zone/1).



## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Bassanio Weekin picks up a discarded item from the ground and says, 'Don't people have enough respect for our grand city to not throw things onto the streets?!*




## Signals

if(e.signal == 1) then


eq.stop();


e.self:MerchantCloseShop();

elseif(e.signal == 2) then


eq.start(58);


e.self:MerchantOpenShop();
end



## Dialog

**You say:** `hail`



>**Bassanio Weekin says:** Go to the taverns if you're looking for talk.

**You say:** `donate`



>**Bassanio Weekin says:** There shall be no donation from me. I have to look after myself first!





end
