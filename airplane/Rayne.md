# Rayne
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `hail`



>**Rayne says:** Great, let us waste no more time! Do you wish to begin your test of Deception, Stealth, or Cunning?

**You say:** `deception`




>**Rayne says:** Deception it is.  Proceed upward through the sky and return to me the honied nectar, a bixie stinger from this plane, a lightning rod, and a bloodsky sapphire for the test of deception and earn Thornstinger, dirk of rampage.

**You say:** `stealth`




>**Rayne says:** Stealth is a must.  Travel among the residents of the sky and bring to me a pegasus statuette, a prismatic sphere, and a fine wool cloak.  In return, the shimmering bracer of protection shall be yours.

**You say:** `cunning`




>**Rayne says:** Cunning, the true source of all rogue power.  Plan and succeed above us and return to me a bronze disc, a Jester's Mask, and some red face paint to complete the test of cunning.  The crystal mask shall be yours if you do so.
end

## Turn-Ins



if( **You turn in:** [Honeyed Nectar](/item/20963), [Bixie Stinger](/item/20994), [Lightning Rod](/item/20995), [Bloodsky Sapphire](/item/20996)) then  



>**Rayne says:** They call this blade 'Rampage Bringer'. Use it wisely and it will serve you well.


 **You receive:**  [Thornstinger](/item/27704) (+100000 exp)

elseif( **You turn in:** [Pegasus Statuette](/item/20949), [Prismatic Sphere](/item/20990), [A fine wool cloak](/item/20991)) then 



>**Rayne says:** I hope you find this bracelet of many colors useful in your journeys. Use its abilities wisely, Soandso.'


 **You receive:**  [Shimmering Bracer of Protection](/item/27703) (+100000 exp)

elseif( **You turn in:** [Bronze Disc](/item/20935), [Jester's Mask](/item/20987), [Red Face Paint](/item/20986)) then 



>**Rayne says:** Take this mask, Soandso. It will aid you in the art of stealth.


 **You receive:**  [Crystal Mask](/item/27702) (+100000 exp)

**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Rayne despawns.**




