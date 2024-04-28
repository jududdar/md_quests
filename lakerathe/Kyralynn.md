# Kyralynn


## Dialog

**You say:** `Hail`



>**Kyralynn says:** Hello. Soandso! I am the shaman Kyralynn. If you have a banded armor, my husband Vrynn and I can form it into a new shaman armor using this totem and some reagents for the ritual. I can use a banded [bracer], [mail], [helm] or [cloak] to form this new armor.

**You say:** `bracer`



>**Kyralynn says:** The bracer requires a banded bracer, 1 dufrenite, a cauldron shell from an aqua goblin lord in Dagnor's Cauldron, and a bull elephant tooth.

**You say:** `helm`



>**Kyralynn says:** The helm requires a banded helm, 1 ground dufrenite, a glacier bear pelt, and an ogreskin chamois from a lizard page.

**You say:** `cloak`



>**Kyralynn says:** The cloak requires a banded cloak, 1 powdered dufrenite, basalt drake scales, and a driftwood pipe from an isle goblin chieftain.

**You say:** `mail`



>**Kyralynn says:** The mail requires banded mail, 1 crushed dufrenite, a lancer swordfish fin, and Grizzleknot bark.
end

## Turn-Ins



local text = "Impressive, do you have the rest?";



if **You turn in:** [Banded Bracer](/item/3061), [Dufrenite](/item/10073), [Cauldron Shell](/item/19031), [Bull Elephant Tooth](/item/19033)


>**Kyralynn says:** Wear this well, Soandso!


 **You receive:**  [Totemic Bracers](/item/4945) (+200 exp)

elseif **You turn in:** [Banded Helm](/item/3053), [Ground Dufrenite](/item/19051), [Glacier Bear Pelt](/item/19042), [Ogreskin Chamois](/item/19040)


>**Kyralynn says:** Wear this well, Soandso!


 **You receive:**  [Totemic Helm](/item/4947) (+200 exp)

elseif **You turn in:** [Banded Cloak](/item/3058), [Powdered Dufrenite](/item/19052), [Basalt Drake Scales](/item/19032), [Driftwood Pipe](/item/19035)


>**Kyralynn says:** Wear this well, Soandso!


 **You receive:**  [Totemic Cloak](/item/4948) (+200 exp)

elseif **You turn in:** [Banded Mail](/item/3056), [Crushed Dufrenite](/item/19050), [Lancer Swordfish Fin](/item/19036), [Grizzleknot Bark](/item/19044)


>**Kyralynn says:** Wear this well, Soandso!


 **You receive:**  [Totemic Breastplate](/item/4946) (+200 exp)

**This NPC *should* return incorrect items given.**
