# Ton Po
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Ton Po says:** So, I have been called upon to test you, and test you I shall. I will give you the option of choosing your test though enlightened one. Shall you take the test of Strength, Sight, or Speed?

**You say:** `strength`



>**Ton Po says:** So be it, the test of strength you shall have. Bring to me a verdant tessera, some finely woven gold mesh,  and some silken strands.  The task will not be easy, but it should serve as an adequate test of strength, for one of your abilities.

**You say:** `sight`



>**Ton Po says:** The test of sight is both a test of body and mind. The mind will allow you to see beyond that which is usually, invisible. Bring me a Gold Disc, a Tiny Ruby, and a Cracked Leather Eyepatch and I will assist you in seeing what should not be seen.

**You say:** `speed`



>**Ton Po says:** The test of speed. Every Monk must be swift if he is to best his opponent. Speed in both mind and body is essential in many facets of life. Return to me an Adumbrate Globe, a Shimmering Opal, and some Dove Slippers and I shall aid your speed of mind.
end

## Turn-Ins



if( **You turn in:** [Finely Woven Gold Mesh](/item/20793), [Silken Strands](/item/20794), [Verdant Tessera](/item/20932)) then 



>**Ton Po says:** You are truly enlightened, Soandso.  I am honored by your presence.


 **You receive:**  [Back Straps of Mastery](/item/27714) (+100000 exp)

elseif( **You turn in:** [Cracked Leather Eyepatch](/item/20796), [Gold Disc](/item/20939), [Tiny Ruby](/item/20795)) then 


>**Ton Po says:** This eye patch once belonged to the great Ton Po. Please, you must take it as you are far more enlightened than I.


 **You receive:**  [Ton Po's Eye Patch](/item/1281) (+100000 exp)

elseif( **You turn in:** [Adumbrate Globe](/item/20946), [Dove Slippers](/item/20798), [Shimmering Opal](/item/20797)) then 


>**Ton Po says:** Take these sandals, Soandso.  It is you who deserves to wear them, not I.


 **You receive:**  [Sandals of Alacrity](/item/1280) (+100000 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Ton Po despawns.**



