# Lelulean
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Lelulean says:** Great, let us waste no more time! I have three tests from which you can choose from. They are Illusion, Metamorphism, and Deception.

**You say:** `illusion`



>**Lelulean says:** Illusion it is.  Proceed upward through the sky and return to me a crimson tessera, a darkstone emerald, and a finely woven cloth cord.  This will prove your abilities to me and I will reward you with a cord of sphinx hair.

**You say:** `metamorphism`



>**Lelulean says:** Metamorphism it is.  Proceed upward through the sky and return to me a silver disk, a bluish stone, and a light cloth mantle.  This will prove your abilities to me and I will reward you with the Wind Walker's Mantle.

**You say:** `deception`



>**Lelulean says:** Deception it is.  Proceed upward through the sky and return to me a rugous globe, a sky pearl, and a silken mask.  This will prove your abilities to me and I will reward you with an ivory mask.
end

## Turn-Ins



if **You turn in:** [Crimson Tessera](/item/20931), [Darkstone Emerald](/item/20767), [Finely Woven Cloth Cord](/item/20768)


>**Lelulean says:** Good work, Soandso, I hope you find this as useful as I find the items you retrieved for me.


 **You receive:**  [Sphinx Hair Cord](/item/1277) (+100000 exp)

elseif **You turn in:** [Bluish Stone](/item/20769), [Light Cloth Mantle](/item/20770), [Silver Disc](/item/20938)


>**Lelulean says:** The Wind Walker's Mantle will sit well upon your shoulders, Soandso.  Be well this day.


 **You receive:**  [Wind Walkers Mantle](/item/1276) (+100000 exp)

elseif **You turn in:** [Rugous Globe](/item/20945), [Silken Mask](/item/20772), [Sky Pearl](/item/20771)


>**Lelulean says:** My thanks to you, Soandso.  Take this mask as a token of my gratitude.


 **You receive:**  [Ivory Mask](/item/1275) (+100000 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Lelulean despawns.**




