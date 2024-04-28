# Gharin
## Dialog


**You say:** `hail`



if **Faction** >= Indifferent then 



>**Gharin says:** Good day! I see they have good stock for the future armies of Qeynos. I, myself, wish to be a soldier one day instead of doing this [job].


else



**Gharin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `job`



if **Faction** >= Indifferent then



>**Gharin says:** I am a [messenger] for Antonius Bayle. Not big enough to fight, but light enough to run all the way to the [Jaggedpine] tomorrow morning. I sort of wish I did not have to go. I'd rather be at the Lion's Mane.


else



**Gharin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `messenger`



if **Faction** >= Indifferent then



>**Gharin says:** I will be taking a private note to the head druid of the Jaggedpine Treefolk. Matter of fact, I am carrying the note right now. But enough about that, if it were not for the mission tomorrow, I could be doing something at the [Lion's Mane].


else



**Gharin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `lion.* mane`



if **Faction** >= Indifferent then



>**Gharin says:** Ahh. The Lion's Mane. If I were there, I would be enjoying a stein of Crow's [special brew]. They are expecting their first shipment of the brew. I believe if I had a few or more of those lagers, I would be very ill. I would probably have to have someone else deliver the note for me. Still, I wish I had one of those fine brews.


else



**Gharin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!


**You say:** `special brew`



if **Faction** >= Indifferent then



>**Gharin says:** Crow's special brew is one of the finest lagers anywhere. It used to be sold only at Crow's bar, but apparently Crow is allowing it into other bars. For a hefty price, too, I assume. This deal is good for decent citizens considering that the other two bars in Qeynos cater to pretty rough crowds.


else



**Gharin says one of the following:**

>I didn't know Slime could speak common.  Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here?  Now go away!

>I wonder how much I could get for the tongue of a blithering fool?  Leave before I decide to find out for myself.

>Oh look..a talking lump of refuse..how novel!

end

## Turn-Ins



local text = "Oh! That's tasty. I guess I could handle a few more.";



if **You turn in:** [Crows Special Brew](/item/13799), [Crows Special Brew](/item/13799), [Crows Special Brew](/item/13799), [Crows Special Brew](/item/13799)


>**Gharin says:** Oohhh! My head. Stop the pub from spinning. I cannot make it to the Jaggedpine feeling like this. Please take this note to Te'Anara of the Treefolk. Here is a little silver for the favor. Thanks. Ooohhhh..


* __Faction:__ [Guards of Qeynos](/faction/262) (50)


* __Faction:__ [Antonius Bayle](/faction/219) (7)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-7)


* __Faction:__ [Circle of Unseen Hands](/faction/223) (-12)


* __Faction:__ [Merchants of Qeynos](/faction/291) (5)


 **You receive:**  [A Sealed Letter](/item/18807) (+250 exp)

**This NPC *should* return incorrect items given.**
