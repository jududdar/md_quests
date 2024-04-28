# Edgar Lemoof
## Dialog

**You say:** `hail`



>**Edgar Lemoof says:** Hiya. I be a fishin'. What, ya need somethin?

**You say:** `armor`



>**Edgar Lemoof says:** Oh ya want some of the druid equipment that Rilla and I make?

**You say:** `druid`



>**Edgar Lemoof says:** I can make ya a mask, cloak, gloves, talisman, belt, and a crook. Just ask about each one and I'll tell ya what ya need to bring so I can make it.

**You say:** `mask`



>**Edgar Lemoof says:** 'For the earth blessed mask you need to bring me a moon jewel, a mark of storms, and an etched fire opal of nature.

**You say:** `cloak`



>**Edgar Lemoof says:** For the earth blessed cloak you need to bring me a star jewel, a mark of the earth, an etched peridot of nature, and a tablet of wolves.

**You say:** `gloves`



>**Edgar Lemoof says:** 'For the earth blessed gloves you need to bring me a cloud jewel, a mark of blossoms, and an etched pearl of nature.

**You say:** `talisman`



>**Edgar Lemoof says:** For the earth blessed talisman you need to bring me a sky jewel, a mark of rain, and an etched opal of nature.

**You say:** `belt`



>**Edgar Lemoof says:** For the earth blessed belt you need to bring me a meteor jewel, a mark of flora, an etched onyx of nature, and an ancient writ of nature.

**You say:** `crook`



>**Edgar Lemoof says:** For the earth blessed crook you need to bring me an astral jewel, mark of fauna, an etched fire emerald of nautre, and a vial of moon dew.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if **You turn in:** [Moon Jewel](/item/4489), [Mark of Storms](/item/5097), [Etched Fire Opal of Nature](/item/5098)


FactionReward(e)


 **You receive:**  [Earth Blessed Veil](/item/3769) (+25000 exp)

elseif **You turn in:** [Star Jewel](/item/4490), [Mark of the Earth](/item/5099), [Tablet of Wolves](/item/5107), [Etched Peridot of Nature](/item/6395)


FactionReward(e)


 **You receive:**  [Earth Blessed Cape](/item/3770) (+25000 exp)

elseif **You turn in:** [Cloud Jewel](/item/4491), [Mark of Blossoms](/item/5108), [Etched Pearl of Nature](/item/5109)


FactionReward(e)


 **You receive:**  [Earth Blessed Gloves](/item/3771) (+25000 exp)

elseif **You turn in:** [Sky Jewel](/item/4492), [Mark of Rain](/item/5110), [Etched Opal of Nature](/item/5116)


FactionReward(e)


 **You receive:**  [Earth Blessed Talisman](/item/3772) (+25000 exp)

elseif **You turn in:** [Meteor Jewel](/item/4493), [Mark of Flora](/item/5117), [Etched Onyx of Nature](/item/5118), [Ancient Writ of Nature](/item/5119)


FactionReward(e)


 **You receive:**  [Earth Blessed Belt](/item/3773) (+25000 exp)

elseif **You turn in:** [Astral Jewel](/item/4494), [Mark of Fauna](/item/5129), [Etched Fire Emerald of Nature](/item/5190), [Vial of Moon Dew](/item/5191)


FactionReward(e)


 **You receive:**  [Earth Blessed Crook](/item/3774) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Edgar Lemoof says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)