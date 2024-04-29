# Mizr N-Mar


## Dialog

**You say:** `hail`



>**Mizr N-Mar says:** Have you come to buy a scroll from me?

**You say:** `coin`



>**Mizr N-Mar says:** So, you want a coin do you?
end

## Turn-Ins




if( **You turn in:** gold = 50) then


>**Mizr N-Mar says:** Ahhh - gold. Here is the rune you desire.


 **You receive:**  [Rune of Fortune](/item/10531) 

elseif( **You turn in:** [Glowing Coin of Tash](/item/10791)) then


>**Mizr N-Mar says:** Ah - the Coin of Tash - and already enchanted by.. ? Tarn? Very good! I have enchanted it further - you must now take the coin to Raine Beteria in the Library of Erudin to get the final enchantment.


 **You receive:**  [Gleaming Coin of Tash](/item/10792) (+1000 exp)

**This NPC *should* return incorrect items given.**
