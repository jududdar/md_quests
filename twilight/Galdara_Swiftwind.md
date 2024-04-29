# Galdara Swiftwind
## Dialog

**You say:** `hail`



>**Galdara Swiftwind says:** Hi, I'm one of master Vornol's four apprentices. My specialty is with all things concerning the element of air.

**You say:** `armor`



>**Galdara Swiftwind says:** You must have spoken with master Vornol. He has me keeping this armor for him and various tasks for those to do who wish to wear it. Tell me are you a magician?

**You say:** `magician`



>**Galdara Swiftwind says:** Very good, the pieces that I have are the sandals, mask, cloak, gloves, choker, belt, and a staff.

**You say:** `sandals`



>**Galdara Swiftwind says:** For the sandals you must bring me an astral jewel, a talisman of wind, and a mark of aeration.

**You say:** `mask`



>**Galdara Swiftwind says:** For the mask you must bring me a sun jewel, a talisman of earth, and a sack of shadowed soil.

**You say:** `cloak`



>**Galdara Swiftwind says:** For the cloak you must bring me a moon jewel, a water idol, a water marked scroll, and a runed ring of water.

**You say:** `gloves`



>**Galdara Swiftwind says:** For the gloves you must bring me a star jewel, petrified bones, and a vial of dark earth.

**You say:** `choker`



>**Galdara Swiftwind says:** For the choker you must bring me a cloud jewel, fiery gourd, and a flaming candle.

**You say:** `belt`



>**Galdara Swiftwind says:** For the belt you must bring me a sky jewel, a vial of the morning mist, fastened links and a water etched wand.

**You say:** `staff`



>**Galdara Swiftwind says:** For the staff you must me a meteor jewel, a fire etched wand, an earth etched wand, and an air etched wand.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Astral Jewel](/item/4494), [Talisman of Wind](/item/4586), [Mark of Aeration](/item/4587)) then 


FactionReward(e)


 **You receive:**  [Sandals of Matter](/item/3690) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Talisman of Earth](/item/4588), [Sack of Shadowed Soil](/item/4589)) then 


FactionReward(e)


 **You receive:**  [Veil of Matter](/item/3691) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Water Idol](/item/4597), [Water Marked Scroll](/item/4598), [Runed Ring of Water](/item/4599)) then 


FactionReward(e)


 **You receive:**  [Cloak of Matter](/item/3692) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Petrified Bones](/item/4600), [Vial of Dark Earth](/item/4601)) then 


FactionReward(e)


 **You receive:**  [Gloves of Matter](/item/3693) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Fiery Gourd](/item/4602), [Flaming Candle](/item/4603)) then 


FactionReward(e)


 **You receive:**  [Choker of Matter](/item/3694) (+25000 exp)

elseif( **You turn in:** [Sky Jewel](/item/4492), [Vial of the Morning Mist](/item/4604), [Fastened Links](/item/4828), [Water Etched Wand](/item/4605)) then 


FactionReward(e)


 **You receive:**  [Belt of Matter](/item/3695) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Fire Etched Wand](/item/4672), [Earth Etched Wand](/item/4674), [Air Etched Wand](/item/4673)) then 


FactionReward(e)


 **You receive:**  [Staff of Matter](/item/3696) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Galdara Swiftwind says:** Soandso take this and use it with pride.

* __Faction:__ [Vornol Transon](/faction/1547) (5)