# Sarah Jelnen
## Dialog

**You say:** `hail`



>*Sarah Jelnen smiles pleasantly eyes meeting yours then speaks, 'Nice to see someone new, I'm one of master Vornol's apprentices.  My specialty is the element of water.*

**You say:** `armor`



>*Sarah Jelnen closes her eyes and sighs wistfully as if remembering some long forgotten bittersweet memory. 'Hafron must have told you about our dearly missed friend Hadon. Very well, are you a shaman?*

**You say:** `shaman`



>**Sarah Jelnen says:** Aye you have the look of one who communes with spirits. The pieces that I have are the mask, cloak, gauntlets, talisman, girdle and spear.

**You say:** `cloak`



>**Sarah Jelnen says:** For the cloak you must get me a cloud jewel, mark of auspice, an avatar's tome, and a rockhopper spirit fetish.

**You say:** `gauntlets`



>**Sarah Jelnen says:** For the gauntlets you must get me a sky jewel, a mark of guidance, and a vitality gem.

**You say:** `girdle`



>**Sarah Jelnen says:** For the girdle you must get me an astral jewel, a mark of augury, an aged runic crutch, and a lined towel.

**You say:** `mask`



>**Sarah Jelnen says:** For the mask you must get me a star jewel, the mark of the oracle, and an aged bone fetish.

**You say:** `spear`



>**Sarah Jelnen says:** For the spear you must get me a sun jewel, a mark of premonition, a darkened shaft, and an oracle orb.

**You say:** `talisman`



>**Sarah Jelnen says:** For the talisman you must get me a meteor jewel, a mark of rage, and a spirit marked ornament.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Cloud Jewel](/item/4491), [Mark of Auspice](/item/4940), [Avatar's Tome](/item/4949), [Rockhopper Spirit Fetish](/item/4950)) then 


FactionReward(e)


 **You receive:**  [Augur's Cloak](/item/3757) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Mark of Guidance](/item/4951), [Vitality Gem](/item/4952)) then 


FactionReward(e)


 **You receive:**  [Augur's Gauntlets](/item/3758) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Augury](/item/4955), [Aged Runic Crutch](/item/4956), [Lined Towel](/item/4957)) then 


FactionReward(e)


 **You receive:**  [Augur's Waistband](/item/3760) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Mark of the Oracle](/item/4938), [Aged Bone Fetish](/item/4939)) then 


FactionReward(e)


 **You receive:**  [Augur's Mask](/item/3756) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Darkened Shaft](/item/4959), [Oracle's Orb](/item/4960), [Mark of Premonition](/item/4958)) then 


FactionReward(e)


 **You receive:**  [Augur's Spear](/item/3761) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Mark of Rage](/item/4953), [Spirit Marked Ornament](/item/4954)) then 


FactionReward(e)


 **You receive:**  [Augur's Talisman](/item/3759) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Sarah Jelnen says:** Soandso take this and use it with pride.

* __Faction:__ [Vornol Transon](/faction/1547) (5)