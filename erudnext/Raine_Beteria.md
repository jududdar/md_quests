# Raine Beteria
## Dialog

**You say:** `hail`



if( **Faction is** >= Indifferent) then



>**Raine Beteria says:** Welcome. I am Raine Beteria.


else



>**Raine Beteria says:** You are lucky to be standing. Leave here immediately or suffer grave consequences! You are not welcome amongst the Craftkeepers.

end

## Turn-Ins




if( **Faction is** >= Indifferent) then


if( **You turn in:** [Blessed Silver Wand](/item/6339),gold = 50) then



>**Raine Beteria says:** Your silver wand has been fully enchanted. Take it and the pouch of silver dust back to the temple of Ro.



 **You receive:**  [Glowing Silver Wand](/item/6340) (+1000 exp)


elseif( **You turn in:** [Gleaming Coin of Tash](/item/10792)) then



>**Raine Beteria says:** Thank you very much. I have always wanted one of these! Hehehe? Just kidding. I see that you have enchanted this coin. I have placed the final enchantment on it - take it back to Romar.



 **You receive:**  [Radiant Coin of Tash](/item/10793) (+1000 exp)


**This NPC *should* return incorrect items given.**
;