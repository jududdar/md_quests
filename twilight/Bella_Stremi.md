# Bella Stremi
## Dialog

**You say:** `hail`



>**Bella Stremi says:** Ah hello and welcome, Soandso. 'Tis a pleasure to see some new faces.  I have the finest wares to be found, be sure to check them out.

**You say:** `wares`



>**Bella Stremi says:** Oh I carry the usual items, food and various other things. I may have something you would be interested in if you are a practitioner of the dark arts.

**You say:** `dark art`



>**Bella Stremi says:** Frantip and I once accepted in trade this set of armor from a necromancer for services rendered. If you happen to be a necromancer perhaps we could work out a deal for the armor.

**You say:** `necromancer`



>**Bella Stremi says:** I have a cap, robes, sleeves, pants, shawl, bracer, and sandals for a necromancer. Frantip has the rest just ask him about armor and I'm sure he'll help you. Which are you interested in?

**You say:** `cap`



>**Bella Stremi says:** For the cap of pestilence you'll have to bring me a sky jewel, an aged gold coin, a dark gem, and a priceless book.

**You say:** `robe`



>**Bella Stremi says:** For the robe of pestilence you'll have to bring me a meteor jewel, a miniature armband, a mark of fortune, and a sun wraith eye.

**You say:** `sleeves`



>**Bella Stremi says:** For the sleeves of pestilence you'll have to bring me an astral jewel, a petrified totem, a frozen hailstone, and a glowing crystal.

**You say:** `pants`



>**Bella Stremi says:** For the pants of pestilence you'll have to bring me a sun jewel, a divining rod, an aged platinum symbol, and a silver sign.

**You say:** `shawl`



>**Bella Stremi says:** For the shawl of pestilence you'll have to bring me a moon jewel an ancient fossil, and some wrought iron shavings.

**You say:** `bracer`



>**Bella Stremi says:** For the bracer of pestilence you'll have to bring me a star jewel, a granite idol, and an ancient silver coin.

**You say:** `sandals`



>**Bella Stremi says:** For the sandals of pestilence you'll have to bring me a cloud jewel, a blackened ornament, and a snake scale sceptre.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if **You turn in:** [Sky Jewel](/item/4492), [Aged Gold Coin](/item/4741), [Dark Gem](/item/4742), [Priceless Book](/item/4743)


FactionReward(e)


 **You receive:**  [Cap of Pestilence](/item/3723) (+25000 exp)

elseif **You turn in:** [Meteor Jewel](/item/4493), [Miniature Armband](/item/4744), [Mark of Fortune](/item/4745), [Sun Wraith Eye](/item/4746)


FactionReward(e)


 **You receive:**  [Robe of Pestilence](/item/3724) (+25000 exp)

elseif **You turn in:** [Astral Jewel](/item/4494), [Petrified Totem](/item/4748), [Frozen Hailstone](/item/4749), [Glowing Crystal](/item/4750)


FactionReward(e)


 **You receive:**  [Sleeves of Pestilence](/item/3725) (+25000 exp)

elseif **You turn in:** [Sun Jewel](/item/4488), [Divining Rod](/item/4751), [Aged Platinum Symbol](/item/4752), [Silver Sign](/item/4753)


FactionReward(e)


 **You receive:**  [Pants of Pestilence](/item/3726) (+25000 exp)

elseif **You turn in:** [Moon Jewel](/item/4489), [Ancient Fossil](/item/4771), [Wrought Iron Shavings](/item/4772)


FactionReward(e)


 **You receive:**  [Shawl of Pestilence](/item/3727) (+25000 exp)

elseif **You turn in:** [Star Jewel](/item/4490), [Granite Idol](/item/4773), [Ancient Silver Coin](/item/4774)


FactionReward(e)


 **You receive:**  [Bracer of Pestilence](/item/3728) (+25000 exp)

elseif **You turn in:** [Cloud Jewel](/item/4491), [Blackened Ornament](/item/4775), [Snake Scale Sceptre](/item/4776)


FactionReward(e)


 **You receive:**  [Sandals of Pestilence](/item/3729) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Bella Stremi says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)