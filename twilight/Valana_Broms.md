# Valana Broms
## Dialog

**You say:** `hail`



>*Valana Broms studies you for a moment and then speaks, 'Greetings, I'm Valana.  Many come here to speak with those in the tower.  What brings you here?*

**You say:** `armor`



>**Valana Broms says:** The armor that I have to reward you is a headband, gi, arm wraps, leggings, shawl, wrist wraps, and sandals. My friend and guard Allise has the rest if you wish to speak with her, just ask about armor.

**You say:** `headband`



>**Valana Broms says:** For the headband you must retrieve for me a sun jewel, a mark of peace, an oblong clay bowl, and a great gem.

**You say:** `gi`



>**Valana Broms says:** For the gi you must retrieve for me a moon jewel, a mark of tranquility, sharpened rock hopper claws, and some etched steel shavings.

**You say:** `arm wraps`



>**Valana Broms says:** For the arm wraps you must retrieve for me a star jewel, a mark of harmony, a triple beaded circlet, and some fresh spring water.

**You say:** `leggings`



>**Valana Broms says:** For the leggings you must retrieve for me a cloud jewel, a mark of meditation, Ralcom's Writ, and a jar of ointment.

**You say:** `shawl`



>**Valana Broms says:** For the shawl you must retrieve for me a sky jewel, a mark of unity and a pewter figurine.

**You say:** `wrist wraps`



>**Valana Broms says:** For the wrist wraps you must retrieve for me a meteor jewel, a mark of true self, and a coiled steel wire.

**You say:** `sandals`



>**Valana Broms says:** For the sandals you must retrieve for me an astral jewel, a mark of form, and some spire spirit dust.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Great Gem](/item/5194), [Mark of Peace](/item/5192), [Oblong Clay Bowl](/item/5193), [Sun Jewel](/item/4488)) then 


FactionReward(e)


 **You receive:**  [Steel Threaded Headband](/item/3775) (+25000 exp)

elseif( **You turn in:** [Etched Steel Shavings](/item/5197), [Mark of Tranquility](/item/5195), [Moon Jewel](/item/4489), [Sharpened Rockhopper Claws](/item/5196)) then 


FactionReward(e)


 **You receive:**  [Steel Threaded Gi](/item/3776) (+25000 exp)

elseif( **You turn in:** [Fresh Spring Water](/item/5244), [Mark of Harmony](/item/5198), [Star Jewel](/item/4490), [Triple Beaded Circlet](/item/5199)) then 


FactionReward(e)


 **You receive:**  [Steel Threaded Arm Wraps](/item/3777) (+25000 exp)

elseif( **You turn in:** [Cloud Jewel](/item/4491), [Jar of Ointment](/item/5247), [Mark of Meditation](/item/5245), [Ralcom's Writ](/item/5246)) then 


FactionReward(e)


 **You receive:**  [Steel Threaded Pants](/item/3778) (+25000 exp)

elseif( **You turn in:** [Mark of Unity](/item/5248), [Pewter Figurine](/item/5249), [Sky Jewel](/item/4492)) then 


FactionReward(e)


 **You receive:**  [Steel Threaded Shawl](/item/3779) (+25000 exp)

elseif( **You turn in:** [Coiled Steel Wire](/item/5251), [Mark of True Self](/item/5250), [Meteor Jewel](/item/4493)) then 


FactionReward(e)


 **You receive:**  [Steel Threaded Wrist Wraps](/item/3780) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Mark of Form](/item/5252), [Spire Spirit Dust](/item/5253)) then 


FactionReward(e)


 **You receive:**  [Steel Threaded Sandals](/item/3781) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Valana Broms says:** Soandso take this and use it with pride.

* __Faction:__ [Vornol Transon](/faction/1547) (5)