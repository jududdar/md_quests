# Gordon Treecaller
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Gordon Treecaller says:** Hello Soandso, I can only hope that my disturbance was necessary. Ahh, you seem to be decently adept with a blade. Would you like to be tested in the element of thunder, the blade, or the art of ranged attack?

**You say:** `element of thunder`




>**Gordon Treecaller says:** One of my greatest allies indeed. Thunder can be very powerful if used properly. Bring me a djinni statuette, a spiroc thunder totem, and a white gold earring. Then you will know the true power of nature.

**You say:** `blade`



>**Gordon Treecaller says:** Very good choice, my blade is my best friend and yours will be as well if you can complete this task. Retrieve an efreeti long sword, an emerald spiroc feather, some bitter honey, and a circlet of thorns. Be careful with the honey, if it is tainted the blade will not come to life.

**You say:** `art of ranged attack`



>**Gordon Treecaller says:** Many of the fools on Norrath don�t realize how powerful a good bow can be. Many dread wolves have met their fate from my bow and you can have the same power if you can bring me back these items. Efreeti war bow, thickened nectar, a sphinx tallow, and a shimmering pearl.
end

## Turn-Ins



if( **You turn in:** [Djinni Statuette](/item/20955), [Spiroc Thunder Totem](/item/20856), [White Gold Earring](/item/20857)) then 







>**Gordon Treecaller says:** Great work, Soandso, take this earring as a token of my admiration.


 **You receive:**  [Thunderforged Earring](/item/14568) (+100000 exp)


**Gordon Treecaller despawns.**

elseif( **You turn in:** [Bitter Honey](/item/20859), [Circlet of Brambles](/item/20860), [Efreeti Long Sword](/item/20858), [Emerald Spiroc Feather](/item/20962)) then 



>**Gordon Treecaller says:** You are indeed a ranger of noble bearing. The sword Arydryidriyorn will do well at your side.


 **You receive:**  [Arydryidriyorn](/item/27732) (+100000 exp)


**Gordon Treecaller despawns.**

elseif( **You turn in:** [Efreeti War Bow](/item/20861), [Thickened Nectar](/item/20969), [Sphinx Tallow](/item/20862), [Shimmering Pearl](/item/20863)) then 



>**Gordon Treecaller says:** You are a walking legend, Soandso. Please take Windstriker. It needs one such as yourself to wield it.


 **You receive:**  [Windstriker](/item/11696) (+100000 exp)


**Gordon Treecaller despawns.**

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Gordon Treecaller despawns.**



