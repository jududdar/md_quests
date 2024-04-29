# Falorn
## On NPC Spawn

**Set a timer** named *depop* for 300 seconds
## Dialog

**You say:** `Hail`



>**Falorn says:** Do not waste my time, Soandso.  Do you wish to take the test of blades or not? Or do you have one of my old trinkets you wish to trade in?

**You say:** `trinkets`



>**Falorn says:** Ahh, I've given out some lesser trinkets in the past that many have gotten bored with.  I'm willing to accept Aerated Pauldrons in trade for Pauldrons of the Blue Sky.

**You say:** `blades`



>**Falorn says:** The test of blades is not easy.  I hope you are as powerful as you are brave.  What do you wish to strive for? Strength, force, or skill?

**You say:** `strength`




>**Falorn says:** Remember, true strength lies not only in the body, but in the mind as well. Return to me a bronze disc, a small pick and a stone amulet. If you manage to do this my runed wind amulet will be yours.

**You say:** `force`





>**Falorn says:** Foolishness or bravery Gendal?  We shall see. Return to me a pearlescent globe, a silver mesh and a spiroc air totem  In return, you will receive both my deepest respect and the aerated pauldrons.

**You say:** `skill`





>**Falorn says:** Test of skill it is. Go upward and retrieve these three items; an ivory tessera, a small ruby, and an azure ring. Return these to me and the azure ruby ring shall be yours.
end

## Turn-Ins



if( **You turn in:** [Bronze Disc](/item/20935), [Small Pick](/item/20972), [Stone Amulet](/item/20973)) then





>**Falorn says:** I am impressed, Soandso. You are stronger than I thought.


 **You receive:**  [Runed Wind Amulet](/item/14569) (+100000 exp)


elseif( **You turn in:** [Pearlescent Globe](/item/20942), [Silver Mesh](/item/20974), [Spiroc Air Totem](/item/20975)) then




 **You receive:**  [Pauldrons of the Blue Sky](/item/27701) (+100000 exp)


elseif( **You turn in:** [Ivory Tessera](/item/20928), [Small Ruby](/item/20970), [Azure Ring](/item/20971)) then




 **You receive:**  [Azure Ruby Ring](/item/14551) (+100000 exp)


**This NPC *should* return incorrect items given.**

## Timer(s)

**Stop timer** named *depop*

**Falorn despawns.**




