# Tiam Khonsir
## Dialog

**You say:** `hail`



>**Tiam Khonsir says:** Greetings, Soandso. Are you a follower of our order, the Deepwater Knights, servants of the Ocean Lord, Prexus?

**You say:** `yes`



>**Tiam Khonsir says:** That is good, Soandso. Our followers are few but our faith is strong. With the efforts of those few, our destiny may be reached in time. We must walk with perseverence and devotion, much like the tides that, over time, can destroy a mighty stone cliff. Have you [come to serve our Lord], Soandso?

**You say:** `come to serve our lord`



>**Tiam Khonsir says:** Then I shall send you on a quest to prove your devotion. No doubt you have seen the vermin kobolds scuttling about the land as fleas upon a mangy dog. The kobolds have a lair on our continent from which they launch their wantonly destructive raids. You are to enter that lair and destroy as many of these dogs as you can. For each molar you bring me, you will receive praise, admiration, and perhaps some coin.

**You say:** `quest of greater importance`



>**Tiam Khonsir says:** Very well then, Soandso, you may be able to help us. Go to Breya and tell her I sent you. She will brief you.

**You say:** `harpoon no more`



>**Tiam Khonsir says:** Well, Soandso, that is unfortunate. Quite a pity, indeed.
end

## Turn-Ins




if **You turn in:** [Kobold Molar](/item/1761)


>**Tiam Khonsir says:** Wonderful work, friend Soandso. One less land dwelling, flea ridden, primitive for our wondrous lord to sweep aside when the apocalypse is upon us. Here is your reward. Perhaps if you gather enough molars, we can offer you a [quest of greater importance].


if(math.random(1,4) == 1) then



 **You receive:** eq.ChooseRandom( [Small Ringmail Sleeves](/item/3120), [Small Ringmail Pants](/item/3123), [Small Ringmail Neckguard](/item/3115), [Small Ringmail Mantle](/item/3117), [Small Ringmail Gloves](/item/3122), [Small Ringmail Coif](/item/3113), [Small Ringmail Coat](/item/3116), [Small Ringmail Cape](/item/3118), [Small Ringmail Bracelet](/item/3121), [Small Ringmail Boots](/item/3124), [Small Ringmail Belt](/item/3119), [Ringmail Sleeves](/item/3108), [Ringmail Skirt](/item/3107), [Ringmail Pants](/item/3111), [Ringmail Neckguard](/item/3103), [Ringmail Mantle](/item/3105), [Ringmail Gloves](/item/3110), [Ringmail Coif](/item/3101), [Ringmail Coat](/item/3104), [Ringmail Cape](/item/3106), [Ringmail Bracelet](/item/3109), [Ringmail Boots](/item/3112), [Large Ringmail Sleeves](/item/3132), [Large Ringmail Pants](/item/3135), [Large Ringmail Neckguard](/item/3127), [Large Ringmail Mantle](/item/3129), [Large Ringmail Gloves](/item/3134), [Large Ringmail Coif](/item/3125), [Large Ringmail Coat](/item/3128), [Large Ringmail Cape](/item/3130), [Large Ringmail Bracelet](/item/3133), [Large Ringmail Boots](/item/3136), [Large Ringmail Belt](/item/3131)) 



note = "You always receive the exp and coin, but only get the item if the statement above succeeds"


* __Faction:__ [Deepwater Knights](/faction/242) (7)


* __Faction:__ [High Council of Erudin](/faction/266) (1)


* __Faction:__ [Heretics](/faction/265) (-1)


 **You receive:** 0 (+3800 exp)


e.other:GiveCash(12,14,5,0); 

**This NPC *should* return incorrect items given.**
;

