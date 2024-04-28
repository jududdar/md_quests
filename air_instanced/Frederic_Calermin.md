# Frederic Calermin
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Frederic Calermin says:** Great, let us waste no more time! I offer to you three challenges. Clarification, Empowerment, and Shielding. Please choose one of these.

**You say:** `clarification`




>**Frederic Calermin says:** Clarification it is. Proceed upward through the sky and return to me a Crimson Tessera, an Ethereal Sapphire, and Feathered Cape.  This will prove your abilities to me and I will reward you with the Bracelet of Clarification.

**You say:** `empowerment`




>**Frederic Calermin says:** Empowerment it is. Proceed upward through the sky and return to me an Iron Disc, a Gem of Empowerment, and a Ceramic Mask. This will prove your abilities to me and I will reward you with the Mask of Empowerment.

**You say:** `shielding`





>**Frederic Calermin says:** Shielding it is. Proceed upward through the sky and return to me a Hyaline Globe, an Ivory Pendant, and a Golden Coffer. This will prove your abilities to me and I will reward you with an Gold White Pendant.
end

## Turn-Ins



if **You turn in:** [Crimson Tessera](/item/20931), [Ethereal Sapphire](/item/20754), [Feathered Cape](/item/20755)


>**Frederic Calermin says:** Take this as your reward.


 **You receive:**  [Bracelet of Clarification](/item/1274) (+100000 exp)


**Frederic Calermin despawns.**

elseif **You turn in:** [Iron Disc](/item/20937), [Gem of Empowerment](/item/20756), [Ceramic Mask](/item/20757)


>**Frederic Calermin says:** This mask will suit you well, mage. Use it sparingly.


 **You receive:**  [Mask of Empowerment](/item/2707) (+100000 exp)


**Frederic Calermin despawns.**

elseif **You turn in:** [Hyaline Globe](/item/20944), [Ivory Pendant](/item/20758), [Golden Coffer](/item/20759)



>**Frederic Calermin says:** A pendant of gold and white, Soandso, wear it and beat back the night.


 **You receive:**  [Gold White Pendant](/item/14557) (+100000 exp)


**Frederic Calermin despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Frederic Calermin despawns.**




