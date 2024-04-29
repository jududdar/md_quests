# Vornol Transon
## Dialog

**You say:** `hail`



>*Vornol Transon pauses for a second staring off into the distance. 'Ah welcome friend. I am Vornol, a summoner of sorts, and master of this tower.'*

**You say:** `magician`



>**Vornol Transon says:** Most excellent what I have is some armor, if you will do few errands for me it is yours. The pieces I have are the cap, robe, sleeves, pants, shawl, and bracer. My apprentice, the lady Galdara, has the rest. Just ask her about armor and she will tell you what you need to do.

**You say:** `cap`



>**Vornol Transon says:** For the cap you will have to bring back to me a sun jewel, a fire idol, a fire marked scroll and a runed ring of fire.

**You say:** `robe`



>**Vornol Transon says:** For the robe you will have to bring back to me a moon jewel, a vial of purified fire, a vial of purified water, and a vial of purified air.

**You say:** `sleeves`



>**Vornol Transon says:** For the sleeves you will have to bring back to me a star jewel, an air idol, an air marked scroll and a runed ring of air.

**You say:** `pants`



>**Vornol Transon says:** For the pants you will have to bring back to me a cloud jewel, an earth idol, an earth marked scroll, and a runed ring of earth.

**You say:** `shawl`



>**Vornol Transon says:** For the shawl you will have to bring back to me a sky jewel, a talisman of burning earth, and a vial of purified earth.

**You say:** `bracer`



>**Vornol Transon says:** For the bracer you will have to bring back to me a meteor jewel, talisman of moisture, and a vial of aqua waters.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Sun Jewel](/item/4488), [Fire Idol](/item/4495), [Fire Marked Scroll](/item/4496), [Runed Ring of Fire](/item/4497)) then 


FactionReward(e)


 **You receive:**  [Cap of Matter](/item/3684) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Vial of Purified Fire](/item/4498), [Vial of Purified Water](/item/4499), [Vial of Purified Air](/item/4506)) then 


FactionReward(e)


 **You receive:**  [Robe of Matter](/item/3685) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Air Idol](/item/4507), [Air Marked Scroll](/item/4508), [Runed Ring of Air](/item/4509)) then 


FactionReward(e)


 **You receive:**  [Sleeves of Matter](/item/3686) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Earth Idol](/item/4510), [Earth Marked Scroll](/item/4511), [Runed Ring of Earth](/item/4512)) then 


FactionReward(e)


 **You receive:**  [Pants of Matter](/item/3687) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Talisman of Burning Earth](/item/4513), [Vial of Purified Earth](/item/4514)) then 


FactionReward(e)


 **You receive:**  [Shawl of Matter](/item/3688) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Talisman of Moisture](/item/4584), [Vial of Aqua Waters](/item/4585)) then 


FactionReward(e)


 **You receive:**  [Bracer of Matter](/item/3689) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Vornol Transon says:** Soandso take this and use it with pride.

* __Faction:__ [Vornol Transon](/faction/1547) (5)