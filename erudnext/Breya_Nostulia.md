# Breya Nostulia
## Dialog

**You say:** `hail`



>*Breya Nostulia stares off into the distance in meditation. Her eyes are a light blue, much like the tropical waters of the ocean between Odus and the mainland. She ignores your greeting.*

**You say:** `tiam sent me`



if( **Faction is** > Indifferent) then 





**You say:** `tiam sent me`





>**Breya Nostulia says:** Seems you've slain quite a few kobolds, then. This is good. You will need to kill many more to fulfill your quest. While the kobolds are fairly primitive, they are an ancient race and have learned to wield the powers of the spirits. This ability is the only thing that has kept us from eradicating them completely. We need you to find instruments of their craft.



**You say:** `instrument`





>**Breya Nostulia says:** There are two items we seek. The shamans carry medicine pouches in which they hold the materials of their craft. Only the more adept shamans are allowed to carry the pouches; seek them out. The other item we seek is of greater importance.



**You say:** `other item`





>**Breya Nostulia says:** The other is a magical bowl from which a highly skilled shaman may divine the future or diagnose illness. Only the wisest of the kobold shamans have the intelligence to use the bowls, or perhaps an outcast with powers that the other, larger kobolds fear. Bring me a kobold medicine pouch and the diviner's bowl and you shall be rewarded with the armor of our trusted knights and priests.




elseif( **Faction is** == Indifferent) then



>**Breya Nostulia says:** You need to prove your dedication to our cause before I can discuss such matters with you.


else



**Breya Nostulia says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!

end

## Turn-Ins



local text = "I'll need both the kobold medicine pouch and the diviner's bowl before I can reward you, Soandso. Good luck.";


if( **Faction is** > Indifferent and  **You turn in:** [Kobold Shamans Pouch](/item/17056), [Diviners Bowl](/item/1766)) then 


>**Breya Nostulia says:** Well done, Soandso. I had a feeling you would return victorious. Here is your reward, the Leggings of Midnight Sea. Wear them with pride for the Ocean Lord. If you are interested in aiding us further, you may want to ask Gans about his brother.





* __Faction:__ [Deepwater Knights](/faction/242) (25)
 

* __Faction:__ [High Council of Erudin](/faction/266) (3)
 

* __Faction:__ [Heretics](/faction/265) (-3)


 **You receive:**  [Midnight Sea Mail Leggings](/item/1762) (+1000 exp)

**This NPC *should* return incorrect items given.**
;