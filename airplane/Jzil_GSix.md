# Jzil GSix


## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Jzil GSix says:** Ah, so you have come to be tested. Many fine things can be your reward. There are three tests which I can administer. Shall you take the test of flight, power, or mind?

**You say:** `flight`






>**Jzil GSix says:** So, you wish the test of flight? So be it. You must return to me a Verdant Tessera, an Ebon Shard, and a Griffons Beak to reap your rewards. May the darkness guide your steps.

**You say:** `test of power`




>**Jzil GSix says:** The test of power it is. Prove yourself worthy of power and bring me a silver disc, spiroc feathers, and a black silk cape. Only then will you know true power.

**You say:** `mind`






>**Jzil GSix says:** The test of mind it shall be.  You must return to me, from this place of air and mist, a rugous globe, some djinni blood, and fine cloth raiment.  Then, and only then, you shall have the reward you deserve!
end

## Turn-Ins



if( **You turn in:** [Verdant Tessera](/item/20932), [Ebon Shard](/item/20780), [Griffons Beak](/item/20781)) then 



>**Jzil GSix says:** Yesss? You do well, Soandso.  Take thisss sssmall token to show my ressspect for you.


 **You receive:**  [Bloody Griffon-Hide Wrist Guard](/item/27712) (+1000000 exp)

elseif( **You turn in:** [Silver Disc](/item/20938), [Spiroc Feathers](/item/20782), [Black Silk Cape](/item/20783)) then 


>**Jzil GSix says:** This feathered cape should be more than enough payment, now be gone from my sight!


 **You receive:**  [Cloak of Spiroc Feathers](/item/1278) (+1000000 exp)

elseif( **You turn in:** [Rugous Globe](/item/20945), [Djinni Blood](/item/20784), [Fine Cloth Raiment](/item/20785)) then 


 **You receive:**  [Bloodsoaked Raiment](/item/1279) (+1000000 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Jzil GSix despawns.**




