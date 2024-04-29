# Neasin Leornic
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Neasin Leornic says:** Great, let us waste no more time! Do you wish to begin your test of concentration, focus, or meditation?

**You say:** `concentration`




>**Neasin Leornic says:** Concentration it is. Proceed upward through the sky and return to me an Azure Tessera, an Augmentor's Gem, and a Grey Damask Cloak. This will prove your ability to concentrate and I will reward you with an Augmentor's Mask.

**You say:** `focus`






>**Neasin Leornic says:** Focus is a must. Travel among the residents of the sky and bring to me an Iron Disc, an Ethereal Opal, and a Woven Skull Cap. This will prove your ability to focus and I will reward you with Al\`Kabors Cap.

**You say:** `meditation`





>**Neasin Leornic says:** Meditation, the fix for all. Fly to those above and return to me a Hyaline Globe, a Sky Topaz, and a High Quality Raiment. If you are successful, I will reward you with the Raiment of Thunder.
end

## Turn-Ins



if( **You turn in:** [Azure Tessera](/item/20930), [Augmentors Gem](/item/20741), [Grey Damask Cloak](/item/20742)) then 



 **You receive:**  [Augmentor's Mask](/item/1272) (+100000 exp)

elseif( **You turn in:** [Iron Disc](/item/20937), [Ethereal Opal](/item/20743), [Woven Skull Cap](/item/20744)) then 


 **You receive:**  [Al\`Kabor's Cap of Binding](/item/1271) (+100000 exp)

elseif( **You turn in:** [Hyaline Globe](/item/20944), [Sky Topaz](/item/20745), [High Quality Raiment](/item/20746)) then 


>**Neasin Leornic says:** This mantle will sit well on your shoulders, Soandso.  Take it as a reward for your troubles.


 **You receive:**  [Raiment of Thunder](/item/1273) (+100000 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Neasin Leornic despawns.**



