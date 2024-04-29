# Nolusia Finharn
## Dialog

**You say:** `hail`



if **Faction** >= Apprehensive then



>**Nolusia Finharn says:** Good evening. Are not the stars beautiful? Somewhere out there, I imagine there is another world and another person staring right back at me. If you have business with me, please save it for the morning in the palace.


else



**Nolusia Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


**You say:** `moodoro`



if **Faction** >= Apprehensive then



>**Nolusia Finharn says:** Moodoro Finharn is my brother. He was a good boy up until he met that accursed halfling named [Flynn] Merrington.


else



**Nolusia Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


**You say:** `flynn`



if **Faction** >= Apprehensive then



>**Nolusia Finharn says:** Flynn Merrington talked my brother into stealing waters from the [Vasty Deep] and selling them to any buyers they could find. The waters from the Vasty Deep are sacred. That is why they started their [business].


else



**Nolusia Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


**You say:** `vasty deep`



if **Faction** >= Apprehensive then



>**Nolusia Finharn says:** The Vasty Deep waters are said to be magical. Of course this is rumor, but it does not stop magic users from all over Norrath from trying to obtain some of the waters.


else



**Nolusia Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


**You say:** `business`



if **Faction** >= Apprehensive then



>**Nolusia Finharn says:** Flynn had talked Moodoro into delivering the waters to him in Qeynos. Eventually Moodoro was caught. He was sentenced to death, but a few spells from yours truly helped him escape death by replacing him with a [doppelganger].


else



**Nolusia Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


**You say:** `doppelganger`



if **Faction** >= Apprehensive then



>**Nolusia Finharn says:** The doppelganger's innards were pulled out its esophagus and Moodoro went to Qeynos to start a new life. Unfortunately, he found Flynn there also. Now they have started up again somehow! My guildmaster is aware of this and fears what the High Council will do to our guild when they find this out. Will you [help] me?


else



**Nolusia Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!


**You say:** `help`



if **Faction** >= Apprehensive then



>**Nolusia Finharn says:** Find out how they get the water. Get me the water and I shall put a poison on the seal of the container. Then you carefully carry the container back to Flynn, not to my brother, and we shall put anto this


else



**Nolusia Finharn says one of the following:**

>I didn't know Slime could speak common. Go back to the sewer before I lose my temper.

>Is that your BREATH, or did something die in here? Now go away!

>I wonder how much I could get for the tongue of a blithering fool? Leave before I decide to find out for myself.

>Oh look, a talking lump of refuse.  How novel!

end

## Turn-Ins




if( **You turn in:** [Eruds Tonic](/item/13118)) then


>**Nolusia Finharn says:** Good work! Now, hold the bottle by the label! When you hand Flynn the bottle, the label will slide off. Bring me the label as proof of the deed.





* __Faction:__ [Craftkeepers](/faction/231) (20)


* __Faction:__ [High Council of Erudin](/faction/266) (2)


* __Faction:__ [Heretics](/faction/265) (-3)


* __Faction:__ [High Guard of Erudin](/faction/267) (3)


 **You receive:**  [Eruds Tonic](/item/13122) (+200 exp)

elseif( **You turn in:** [Label of Erud's Tonic](/item/13123)) then


>**Nolusia Finharn says:** Fantastic. Now I can rest assured that my brother stands a better chance of finding the right path without that manipulating little man around. Master Lanken can rest assured that the waters are safe from abuse.





* __Faction:__ [Craftkeepers](/faction/231) (30)


* __Faction:__ [High Council of Erudin](/faction/266) (3)


* __Faction:__ [Heretics](/faction/265) (-4)


* __Faction:__ [High Guard of Erudin](/faction/267) (4)


 **You receive:** eq.ChooseRandom( [Eruds Tonic](/item/13122), [Rusty Long Sword](/item/5019), [Splintering Club](/item/6017), [Rusty Scimitar](/item/5021), [Rusty Short Sword](/item/5013)) (+0 exp)

**This NPC *should* return incorrect items given.**
;

