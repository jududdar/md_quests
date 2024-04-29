# Gandari
## Dialog

**You say:** `hail`



>**Gandari says:** Most call me Gandari the Terse.  You here for [ivy armor]?

**You say:** `ivy armor`



>**Gandari says:** I reward brave rangers with ivy etched armor - [Helm]s, [Tunic]s, [Sleeves], and [Bracers]. [Interested]?

**You say:** `bracer`



>**Gandari says:** I do not haggle, I do not bargain. The Bottom of the Rune of Ivy from the plains of Everfrost, a Watery Ring from the Cauldron of Tears and a Fire Emerald to warm my heart. Bring these to me and you shall earn your reward.

**You say:** `helm`



>**Gandari says:** I do not haggle, I do not bargain. The Top of the Rune of Ivy from the Castle Mistmoore, a Cyclops Charm from Tarskuk and a Sapphire of Sky Blue. Bring these to me and you shall earn your reward.

**You say:** `sleeve`



>**Gandari says:** I do not haggle, I do not bargain. A Heart of Fire from the Caverns of Solusek, the Left side of the Rune of Ivy from the Griffon Grimfeather and two Star Rubies of sparkling hue. Bring these to me and you shall earn your reward.

**You say:** `tunic`



>**Gandari says:** I do not haggle, I do not bargain. The Skull of Meldrath, the Right side of the Rune of Ivy from the Thistle Brownie and two Rubies of Fiery Red. Bring these to me and you shall earn your reward.
end

## Turn-Ins



local text1 = "Wait, Soandso, are you not forgetting something?";





if( **You turn in:** [Rune of Ivy](/item/10569), [Water Ring](/item/10546), [Fire Emerald](/item/10033)) then 


>**Gandari says:** Well done. May Karana bless your soul.


* __Faction:__ [Kithicor Residents](/faction/269) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


 **You receive:**  [Ivy Etched Bracer](/item/3189) (+10000 exp)

elseif( **You turn in:** [Rune of Ivy](/item/10566), [Cyclops Charm](/item/10570), [Sapphire](/item/10034)) then 


>**Gandari says:** Well done. May Karana bless your soul.


* __Faction:__ [Kithicor Residents](/faction/269) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


 **You receive:**  [Ivy Etched Helm](/item/3181) (+10000 exp)

elseif( **You turn in:** [Heart of Fire](/item/10548), [Rune of Ivy](/item/10568), [Star Ruby](/item/10032), [Star Ruby](/item/10032)) then 


>**Gandari says:** Well done. May Karana bless your soul.


* __Faction:__ [Kithicor Residents](/faction/269) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


 **You receive:**  [Ivy Etched Sleeves](/item/3188) (+10000 exp)

elseif( **You turn in:** [Skull of Meldrath](/item/10571), [Rune of Ivy](/item/10567), [Ruby](/item/10035), [Ruby](/item/10035)) then 


>**Gandari says:** Well done. May Karana bless your soul.


* __Faction:__ [Kithicor Residents](/faction/269) (10)


* __Faction:__ [Protectors of Pine](/faction/302) (1)


* __Faction:__ [Jaggedpine Treefolk](/faction/272) (1)


* __Faction:__ [Unkempt Druids](/faction/324) (-1)


 **You receive:**  [Ivy Etched Tunic](/item/3184) (+10000 exp)

**This NPC *should* return incorrect items given.**






