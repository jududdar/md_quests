# gem cutter skeleton




## Dialog

**You say:** `Hail`



e.self:DoAnim(39);


>*gem cutter skeleton appears to be busy cutting a green gem; upon your greeting, it jumps, fleshless hands slipping carelessly and breaking the gem into powder.*


**Set a timer** named *distracted* for 2 seconds

**You say:** `green gem`



>**gem cutter skeleton says:** The greenest of gems I seek! Jade too brittle, emerald too hard, but [dufrenite]! Ahh, now there is a gem amongst gems.

**You say:** `dufrenite`



>**gem cutter skeleton says:** Yes, dufrenite! Find me a dufrenite to replace the one you made me break. Now go!
end

## Turn-Ins



if **You turn in:** [Dufrenite](/item/10073)


>*gem cutter skeleton eyes sparkle as you hand it the gem.*


>**gem cutter skeleton says:** Yes! Yes! This is the greenest of gems!


 **You receive:**  [Dread Diamond](/item/12946) (+3000 exp)


>**gem cutter skeleton says:** Worth more to you crushed, that is! Find a spectral pestle, and crush it to dust!


**Set a timer** named *cutting* for 4 seconds

**This NPC *should* return incorrect items given.**

## Timer(s)

if(e.timer == "distracted") then


e.self:DoAnim(20);


>**gem cutter skeleton says:** Blast it! Distracted me you have! Now I need a new [green gem]!


**Stop timer** named *distracted*

if(e.timer == "cutting") then


>*gem cutter skeleton carries on cutting gems, oblivious to your presence.*


e.self:DoAnim(39);


**Stop timer** named *cutting*
end





