# Giwin Mirakon
## Dialog

local qglobals = eq.get_qglobals(e.other);

local zeks = tonumber(qglobals.zeks) or 0;


**You say:** `hail`




if ( zeks > 1 ) then



**Message:** <span class="text-warning">*Giwin Mirakon tells you, 'Well then, it took you long enough to get here.  The Zeks have grown tired of waiting for your arrival.  They have retired to their quarters.  I think that you should seek them out, they must have a warm welcome for someone with such a warring spirit!  Do not mind the minions of this realm, it is within their nature to challenge any that come within their reach.  Press on and find the Zeks!'*</span>


else



**Message:** <span class="text-warning">*Giwin Mirakon tells you, 'Who are you to talk to me?  Are you a Warrior of Rallos?  What are you doing here?!  Maybe you should leave before you make me angry.'*</span>

end

## Turn-Ins


local itemInst, item;



for i = 1, 4 do




itemInst = e.trade["item"..i];





if ( itemInst and itemInst.valid ) then



item = itemInst:GetItem();






>**Giwin Mirakon says:** Thanks for the "..itemInst:GetName().." Soandso.







if ( item:NoDrop() == 255 and e.self:CountLoot() < 30 ) then




e.self:RemoveItem(itemInst:GetID()) 




e.self:AddItem(itemInst:GetID(), itemInst:GetCharges(), true);



end
