# Trizpo Tobbnokcog
## Dialog

**You say:** `hail`



>**Trizpo Tobbnokcog says:** Hi there, who are you?  What are you doing here? Oh I'm one of Vornol's four apprentices.  I specialize in the element of earth.

**You say:** `armor`



>**Trizpo Tobbnokcog says:** Oh you've been to see Gazoon on his island. Yep he gave me some of his fancy finger waggler armor, are ya a wizard?

**You say:** `wizard`



>**Trizpo Tobbnokcog says:** Wonderful, then you'll probably be wanting the mask, cloak, gloves, choker, belt and staff I have

**You say:** `mask`



>**Trizpo Tobbnokcog says:** For the mask you'll have to get me a meteor jewel, a mark of potential, and an iron tipped wand.
  
**You say:** `cloak`



>**Trizpo Tobbnokcog says:** For the cloak you'll have to get me an astral jewel, a mark of temper, a vial of firewater, and some iced nectar.
  
**You say:** `gloves`



>**Trizpo Tobbnokcog says:** For the gloves you'll have to get me a sun jewel, a mark of might, and a book of solutions.
  
**You say:** `choker`



>**Trizpo Tobbnokcog says:** For the choker you'll have to get me a moon jewel, a mark of destruction, and a stick of mastery.
  
**You say:** `belt`



>**Trizpo Tobbnokcog says:** For the belt you'll have to get me a star jewel, a mark of thaumaturgy, a loop of energy, and a small magnifying lens.
  
**You say:** `staff`



>**Trizpo Tobbnokcog says:** For the staff you'll have to get me a cloud jewel, a mark of detonation, opaque glasses, and a pyro wand.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if **You turn in:** [Loop of Energy](/item/4736), [Mark of Thaumaturgy](/item/4735), [Small Magnifying Lens](/item/4738), [Star Jewel](/item/4490)


FactionReward(e)


 **You receive:**  [Belt of Detonation](/item/3721) (+25000 exp)

elseif **You turn in:** [Mark of Destruction](/item/4734), [Moon Jewel](/item/4489), [Stick of Mastery](/item/4737)


FactionReward(e)


 **You receive:**  [Choker of Detonation](/item/3720) (+25000 exp)

elseif **You turn in:** [Astral Jewel](/item/4494), [Iced Nectar](/item/4731), [Mark of Temper](/item/4729), [Vial of Firewater](/item/4730)


FactionReward(e)


 **You receive:**  [Cloak of Detonation](/item/3718) (+25000 exp)

elseif **You turn in:** [Book of Solutions](/item/4733), [Mark of Might](/item/4732), [Sun Jewel](/item/4488)


FactionReward(e)


 **You receive:**  [Gloves of Detonation](/item/3719) (+25000 exp)

elseif **You turn in:** [Cloud Jewel](/item/4491), [Mark of Detonation](/item/4739), [Opaque Glasses](/item/4740), [Pyro Wand](/item/5973)


FactionReward(e)


 **You receive:**  [Staff of Detonation](/item/3722) (+25000 exp)

elseif **You turn in:** [Iron Tipped Wand](/item/4728), [Mark of Potential](/item/4727), [Meteor Jewel](/item/4493)


FactionReward(e)


 **You receive:**  [Veil of Detonation](/item/3717) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Trizpo Tobbnokcog says:** Soandso take this and use it with pride.

* __Faction:__ [Vornol Transon](/faction/1547) (5)