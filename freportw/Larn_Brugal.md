# Larn Brugal
## Dialog

**You say:** `hail`



>**Larn Brugal says:** Good day to you Soandso I hope you yearn to become a Steel Warrior as we all are here in the Bunker. We are in need of more recruits to continue the [war].

**You say:** `war`



>**Larn Brugal says:** The war I speak of is the one we Steel Warriors have sworn to wage agianst [Clan Deathfist] in the Commonlands. We are doing a fine job but we require more weapons. We are expecting a shipment of blades from Groflahs Forge. We require a warrior of the bunker to [get our shipment]. Maybe you.

**You say:** `clan deathfist`



>**Larn Brugal says:** If you do not know of Clan Deathfist go ask Cain who they are. He will not only tell you he will sign you up to help fight our war!

**You say:** `shipment`



if **Faction** >= Amiable then



>**Larn Brugal says:** We would be most thankful for your service. Please take this voucher over to Groflah at Groflahs Forge in North Freeport. He will give you the shipment of weapons.



**You receive:**  [A Sealed Letter](/item/18820)


elseif( **Faction is** == Indifferent) then



>**Larn Brugal says:** The Steel Warriors have no cause to dislike you, but you have yet to truly prove your worth to this guild.


else



>**Larn Brugal says:** Your head shall look grand mounted on the wall of the Steel Warriors Arena!!

end

## Turn-Ins



local text = "This is only one sword. I requested four altogether. You shall not get your payment until I get my fourth sword."


if **Faction** >= Amiable and  **You turn in:** [Raw Short Sword 1](/item/12241), [Raw Short Sword 2](/item/12242), [Raw Short Sword 3](/item/12243), [Raw Short Sword 4](/item/12244)


>**Larn Brugal says:** Good work, Soandso. The bunker shall be well stocked. Here you are, my friend. Take this raw blade. You can take it to Groflah - he will sharpen and polish it for you. It should be a formidable weapon.


* __Faction:__ [Steel Warriors](/faction/311) (20)


* __Faction:__ [Guards of Qeynos](/faction/262) (4)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (-3)


* __Faction:__ [The Freeport Militia](/faction/330) (-3)


* __Faction:__ [Knights of Truth](/faction/281) (4)


 **You receive:** None 

**This NPC *should* return incorrect items given.**
;