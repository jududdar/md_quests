# an Iksar hermit
## Dialog

**You say:** `hail`



>*an Iksar hermit looks at you with one good eye.  His left eye is covered with pus.  'I seek a [great sorcerer].*

**You say:** `great sorcerer`



if **Faction** >= Amiable +200 then



>*an Iksar hermit hands you a flaxen hilt or handle of sorts. It has four round slots on one 'Insert within what used to be. Return it to me when all is complete. With it shall you gain your Sorcerer's Skullcap. Go and prove your knowledge.*



**You receive:**  [A Flaxen Hilt](/item/17195)


else



>**an Iksar hermit says:** Greatness comes from many deeds.  You have more work to do.

end

## Turn-Ins



local text = "All is not complete. A cap and the rest, which was asked for, is required.";



if( **You turn in:** [Barbed Scaled Whip](/item/12886), [Sorcerer Skullcap](/item/4266)) then


>*an Iksar hermit takes the flail and vanishes with a brilliant flash!! Within your hands appears a skullcap. You hear a voice echo through the cave. Well done. You are a formidable necromancer. We thank you.*


 **You receive:**  [Necromancer Skullcap](/item/4267) (+10000 exp)


* __Faction:__ [Brood of Kotiz](/faction/443) (15)


* __Faction:__ [Legion of Cabilis](/faction/441) (5)


**an Iksar hermit despawns.**

**This NPC *should* return incorrect items given.**
 