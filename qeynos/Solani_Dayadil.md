# Solani Dayadil
## On NPC Spawn

**Set a timer** named *pick_up* for 2 seconds

e.self:SetRunning(true);
## Timer(s)

if ( e.timer == "pick_up" ) then




while ( e.self:CheckGround() ) do



>*Solani Dayadil picks up a discarded item from the ground and says, 'Don't people have enough respect for our grand city to not throw things onto the streets?!*


## Signals

if(e.signal == 1) then


eq.stop();


e.self:MerchantCloseShop();

elseif(e.signal == 2) then


eq.start(59);



e.self:MerchantOpenShop();
end

## Dialog

**You say:** `hail`



>**Solani Dayadil says:** If you are a fellow merchant. I must warn you of the inevitable tax increase. Antonius Bayle is soon to make a [deal] with the people of Surefall Glade.

**You say:** `deal`



>**Solani Dayadil says:** Bayle is soon to sign a law which will raise the taxes on all bear hides. This is to keep the purchase of the hides to a minimum.  All this to keep the treehuggers happy!!

**You say:** `donate`



>**Solani Dayadil says:** Did you not hear about the [deal] with Surefall Glade?! I will have little money to EAT, let alone donate to another person's cause!


end
