# an elven priest
## Dialog

**You say:** `king is dead`



>**an elven priest says:** Dead you say? My goodness! Did you manage to slay the warlord too? If you provide me with proof of his death, I can enchant the mace the dwarf gave you as payment. But, I will require the proof first!
end

## Turn-Ins



local text = "Have you the other item I require?";


if( **You turn in:** [Bracers of Battle](/item/2301)) then


>**an elven priest says:** Erollisi be praised! You slew the orc lord! Well, here is a token of my appreciation! Should you wish to have that mace enchanted, just hand me the mace and my token and I shall uphold myof the bargain!





 **You receive:**  [Prayer Cloth of Tunare](/item/1900) (+6000 exp)

elseif( **You turn in:** [Dwarven Mace](/item/6315), [Prayer Cloth of Tunare](/item/1900)) then


>**an elven priest says:** As promised, here is your mace. Let it not fall into dark hands as its power is hidden until combat when it will reveal its true nature. Fare thee well!





 **You receive:**  [Screaming Mace](/item/6305) (+6000 exp)


**an elven priest despawns.**

**This NPC *should* return incorrect items given.**
;
