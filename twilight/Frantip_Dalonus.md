# Frantip Dalonus
## Dialog

**You say:** `hail`



>*Frantip Dalonus smiles briefly. 'Greetings to ye Soandso. If you be needin' the goods I've got 'em.*

**You say:** `armor`



>**Frantip Dalonus says:** Ah yes, I've been trying to get rid of this armor for some time. Do you happen to be a necromancer?

**You say:** `necromancer`



>**Frantip Dalonus says:** Very good! I have the veil, cloak, gloves, choker, belt, and staff. Which do you want?

**You say:** `veil`



>**Frantip Dalonus says:** For the veil of pestilence you will have to go retrieve for me a sky jewel, a jeweled rod, and a bronze brazier.

**You say:** `cloak`



>**Frantip Dalonus says:** For the cloak of pestilence you will have to go retrieve for me a meteor jewel, a hardened agate, a veiled lantern, and a white garnet.

**You say:** `gloves`



>**Frantip Dalonus says:** For the gloves of pestilence you will have to go retrieve for me an astral jewel, an antique lantern, and a glowing meteor fragment.

**You say:** `choker`



>**Frantip Dalonus says:** For the choker of pestilence you will have to go retrieve for me a sun jewel, an ancient relic of Tzon, and a fluorescent gem.

**You say:** `belt`



>**Frantip Dalonus says:** For the belt of pestilence you will have to go retrieve for me a moon jewel, an ancestral statuette, some dark hued wood, and an ocher gem.

**You say:** `staff`



>**Frantip Dalonus says:** For the staff of pestilence you will have to go retrieve for me a star jewel, some cultured spirits, some golden mushrooms, and a gem of awe.
end

## Turn-Ins



local text = "You have done well to bring me this, but there is more needed before you get your reward.";



if( **You turn in:** [Sky Jewel](/item/4492), [Jeweled Rod](/item/4777), [Bronze Brazier](/item/4778)) then 


FactionReward(e)


 **You receive:**  [Veil of Pestilence](/item/3730) (+25000 exp)

elseif( **You turn in:** [Meteor Jewel](/item/4493), [Hardened Agate](/item/4779), [Veiled Lantern](/item/4781), [White Garnet](/item/4782)) then 


FactionReward(e)


 **You receive:**  [Cape of Pestilence](/item/3731) (+25000 exp)

elseif( **You turn in:** [Astral Jewel](/item/4494), [Antique Lantern](/item/4783), [Glowing Meteor Fragment](/item/4784)) then 


FactionReward(e)


 **You receive:**  [Gloves of Pestilence](/item/3732) (+25000 exp)

elseif( **You turn in:** [Sun Jewel](/item/4488), [Ancient Relic of Tzon](/item/4785), [Fluorescent Gem](/item/4786)) then 


FactionReward(e)


 **You receive:**  [Choker of Pestilence](/item/3733) (+25000 exp)

elseif( **You turn in:** [Moon Jewel](/item/4489), [Ancestral Statuette](/item/4787), [Dark Hued Wood](/item/4788), [Ocher Gem](/item/4789)) then 


FactionReward(e)


 **You receive:**  [Belt of Pestilence](/item/3734) (+25000 exp)

elseif( **You turn in:** [Star Jewel](/item/4490), [Cultured Spirits](/item/4790), [Golden Mushrooms](/item/4791), [Gem of Awe](/item/4792)) then 


FactionReward(e)


 **You receive:**  [Staff of Pestilence](/item/3735) (+25000 exp)

**This NPC *should* return incorrect items given.**

function FactionReward(e)

>**Frantip Dalonus says:** Soandso take this and use it with pride.

* __Faction:__ [Katta Castellum Citizens](/faction/1502) (5)

* __Faction:__ [Validus Custodus](/faction/1503) (1)

* __Faction:__ [Magus Conlegium](/faction/1504) (1)

* __Faction:__ [Citizens of Seru](/faction/1499) (-2)

* __Faction:__ [Seru](/faction/1483) (-1)

* __Faction:__ [Shoulders of Seru](/faction/1487) (-1)