# Palatos Kynarn
## Dialog

**You say:** `hail`



>**Palatos Kynarn says:** What do you want?  Can't you see that I wish to be alone?!  I have no need nor desire to speak with anyone.  I have a minor dilemma to ponder and the only person I wish to speak with is the [captain].

**You say:** `captain`



>**Palatos Kynarn says:** If you have to ask that, you should not be in this fine establishment.

**You say:** `danaria sent me`



>**Palatos Kynarn says:** If you are working for Danaria, you have been misguided. You will go back to her empty handed. Now leave. The [captain] and I have some business to discuss.

**You say:** `portrait`



>**Palatos Kynarn says:** You have the portrait! Give it to me... <Hic!> Danaria will not get it...
end

## Turn-Ins



local text = "Mmmm...  more...  must... drown... sorrow...";


if( **You turn in:** [Capt. Orlin's Spiced Ale](/item/13817), [Capt. Orlin's Spiced Ale](/item/13817), [Capt. Orlin's Spiced Ale](/item/13817), [Capt. Orlin's Spiced Ale](/item/13817)) then 


>**Palatos Kynarn says:** Ahh... I... <Hic!> Need help... <Hic!>  You... take this... Go build... boat beacon. <Hic!>  Ask gnomes about... <Hic!> boat beacon. They know how... Then bring back... <Hic!> Unnnhh! Prexus help me! I will never drink again.







* __Faction:__ [Craftkeepers](/faction/231) (2)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


* __Faction:__ [High Guard of Erudin](/faction/267) (1)




 **You receive:**  [Beacon Mount](/item/12145) (+100 exp)


elseif( **You turn in:** [Boat Beacon](/item/13818)) then


>**Palatos Kynarn says:** Thanks.. That saved me a lot of money. Now I can spend more time with the captain before I give this back to Lenka Stoutheart. Here is a little so...mething.





* __Faction:__ [Craftkeepers](/faction/231) (10)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [High Guard of Erudin](/faction/267) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** 0 (+20000 exp)

elseif( **You turn in:** [AkAnons Portrait](/item/12146)) then


>**Palatos Kynarn says:** Wise decision!! Little reward for a large deed. Bye.





* __Faction:__ [Craftkeepers](/faction/231) (5)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [High Guard of Erudin](/faction/267) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** 0 (+200 exp)

**This NPC *should* return incorrect items given.**





