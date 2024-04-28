# Vrynn


## Dialog

**You say:** `hail`



>**Vrynn says:** Greetings, spiritwalker. I am called Vrynn. If you have banded armor, my wife Kyralynn and I can form it into a new shaman armor using this totem and some reagents for the ritual. I make armor from banded [boots], [gauntlets], [sleeves], and [leggings].

**You say:** `boots`



>**Vrynn says:** The boots require banded boots, 1 dufrenite, an orc chief's tongue from Lesser Faydark, and terror spines from a tentacle terror in Najena.

**You say:** `gauntlets`



>**Vrynn says:** The gauntlets require banded gauntlets, 1 crushed dufrenite, a mammoth rib bone, and a griffenne downfeather.

**You say:** `sleeves`



>**Vrynn says:** The sleeves require banded sleeves, 1 ground dufrenite, ghoul carrion from Estate of Unrest, and charger hoof chips.

**You say:** `leggings`



>**Vrynn says:** The leggings require banded leggings, 1 powdered dufrenite, a Permafrost snowball from a goblin wizard, and bone barbs from Estate of Unrest.
end

## Turn-Ins



local text = "Impressive, do you have the rest?";


if **You turn in:** [Banded Boots](/item/3064), [Dufrenite](/item/10073), [Chiefs Tongue](/item/19039), [Terror Spines](/item/19041)


>**Vrynn says:** Wear this well, Soandso!


 **You receive:**  [Totemic Boots](/item/4941) (+200 exp)

elseif **You turn in:** [Banded Gauntlets](/item/3062), [Crushed Dufrenite](/item/19050), [Mammoth Rib Bone](/item/19043), [Griffenne Downfeather](/item/19046)


>**Vrynn says:** Wear this well, Soandso!


 **You receive:**  [Totemic Gauntlets](/item/4942) (+200 exp)

elseif **You turn in:** [Banded Sleeves](/item/3060), [Ground Dufrenite](/item/19051), [Ghoul Carrion](/item/19038), [Charger Hoof Chips](/item/19045)


>**Vrynn says:** Wear this well, Soandso!


 **You receive:**  [Totemic Vambraces](/item/4943) (+200 exp)

elseif **You turn in:** [Banded Leggings](/item/3063), [Powdered Dufrenite](/item/19052), [Permafrost Snowball](/item/19034), [Bone Barbs](/item/19037)


>**Vrynn says:** Wear this well, Soandso!


 **You receive:**  [Totemic Greaves](/item/4944) (+200 exp)

**This NPC *should* return incorrect items given.**
