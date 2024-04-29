# Gamali
## Dialog

**You say:** `hail`



>*Gamali Glances up at you for a moment and then grunts and turns back toward the water.*
end

## Turn-Ins



local bottles = 0



if( **You turn in:** [Bottle](/item/16598), [Bottle](/item/16598), [Bottle](/item/16598), [Bottle](/item/16598)) then


bottles = 4;

elseif( **You turn in:** [Bottle](/item/16598), [Bottle](/item/16598), [Bottle](/item/16598)) then


bottles = 3;

elseif( **You turn in:** [Bottle](/item/16598), [Bottle](/item/16598)) then


bottles = 2;

elseif( **You turn in:** [Bottle](/item/16598)) then


bottles = 1;



if(bottles > 0) then


repeat



>*Gamali leans over and fills the bottle with cool clear liquid. Gamali says, 'So Merchant Ahlam has you doing his errands now does he? Well, here's your water. I can assure you it's of good quality.' She turns away and begins staring out into the distance.*



 **You receive:**  [Bottle of fresh water](/item/31761) 



bottles = bottles - 1;


until bottles == 0


bottles = 0;

**This NPC *should* return incorrect items given.**
