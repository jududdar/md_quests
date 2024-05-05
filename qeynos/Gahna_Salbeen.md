# Gahna Salbeen



[Gahna Salbeen](/npc/1120) is a level 30 Human Shopkeeper that spawns in [South Qeynos](/zone/1).



## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds


## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Gahna Salbeen picks up a discarded item from the ground and says, 'Don't people have enough respect for our grand city to not throw things onto the streets?!*




## Signals

if(e.signal == 1) then


eq.stop();


e.self:MerchantCloseShop();

elseif(e.signal == 2) then


eq.start(57);


e.self:MerchantOpenShop();
end



## Dialog

**You say:** `hail`



>**Gahna Salbeen says:** Greetings. This is a grand city. I plan to make much profit here.

**You say:** `donate`



>**Gahna Salbeen says:** Qeynos is the place where I will make a fortune. In order to do that, I must hoard all my coins and not donate to ancient religions.



end
