# Ithvol K-Jasn



## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Ithvol K-Jasn says:** Hail, Soandso! I sense the gift of hatred in your aura. What status do you hold within these Spires?


elseif **Faction** >= Indifferent then



>**Ithvol K-Jasn says:** Although I sense the hate building within you, you have not yet done enough service to this temple to be trusted!


else



>**Ithvol K-Jasn says:** You are worthless and pathetic! You could never be of service to our temple!  Begone before your innards decorate our walls!




**You say:** `initiate`



if **Faction** >= Amiable then



>**Ithvol K-Jasn says:** Well met, Initiate Soandso. If you desire to raise your station in this temple, I have a task for you. Are you willing to accept the task I am about to set before you?


elseif **Faction** >= Indifferent then



>**Ithvol K-Jasn says:** Although I sense the hate building within you, you have not yet done enough service to this temple to be trusted!


else



>**Ithvol K-Jasn says:** You are worthless and pathetic! You could never be of service to our temple!  Begone before your innards decorate our walls!




**You say:** `willing`



if **Faction** >= Amiable then



>**Ithvol K-Jasn says:** As an initiate of the Spires, you have proven your hatred of the halflings who are desecrating our forest with their feeble shrines and camps. They persist in their hopeless task and seem to anticipate many of our tactics against them. Go out into the Nektulos and slay the one called Master Whoopal. Take his head to Draxiz N'Ryt so that he may probe the brain.


elseif **Faction** >= Indifferent then



>**Ithvol K-Jasn says:** Although I sense the hate building within you, you have not yet done enough service to this temple to be trusted!


else



>**Ithvol K-Jasn says:** You are worthless and pathetic! You could never be of service to our temple!  Begone before your innards decorate our walls!




**You say:** `disciple`



if **Faction** >= Amiable then



>**Ithvol K-Jasn says:** I have an important task for a disciple of Hate such as yourself. It is no secret that King Naythox Thex wishes to expand the Teir'Dal Empire to the continent of Faydwer. We have a camp established in the Lesser Faydark near the stronghold of the vampire lord, Mayong Mistmoore. The camp is constantly under siege by the Fier'Dal and Koada'Dal and must rely on the support of Neriak for supplies necessary to survival. Are you willing to serve your King and Empire by delivering the provisions?


elseif **Faction** >= Indifferent then



>**Ithvol K-Jasn says:** Although I sense the hate building within you, you have not yet done enough service to this temple to be trusted!


else



>**Ithvol K-Jasn says:** You are worthless and pathetic! You could never be of service to our temple!  Begone before your innards decorate our walls!




**You say:** `deliver the provisions`



if **Faction** >= Amiable then



>**Ithvol K-Jasn says:** The provisions are crated and prepared for shipment by Dran Slug Rembor. Go to his establishment in the Foreign Quarter and tell him Ithvol sent you. Make haste, young disciple of Hate! The fate of the Empire hangs upon our support of the Faydark Camp!


elseif **Faction** >= Indifferent then



>**Ithvol K-Jasn says:** Although I sense the hate building within you, you have not yet done enough service to this temple to be trusted!


else



>**Ithvol K-Jasn says:** You are worthless and pathetic! You could never be of service to our temple!  Begone before your innards decorate our walls!



end

## Turn-Ins



if **You turn in:** [Head of a Halfling Spy](/item/12497), [Initiate Symbol of Innoruuk](/item/1369)


>*Ithvol K-Jasn You have focused the hate within you and discovered that hate and rage are not the same. Hate can be calculating and deceptive. For your service in defending the Kingdom of King Naythox Thex from the halfling invaders, I award you the disciple symbol of Innoruuk. Wear it with pride, Soandso.*


* __Faction:__ [Priests of Innoruuk](/faction/340) (50)


* __Faction:__ [King Naythox Thex](/faction/278) (7)


* __Faction:__ [Clerics of Tunare](/faction/226) (-17)


* __Faction:__ [Priests of Life](/faction/341) (-12)


* __Faction:__ [Priests of Marr](/faction/362) (-7)


* __Faction:__ [Primordial Malice](/faction/1522) (-200)


 **You receive:**  [Disciple Symbol of Innoruuk](/item/1370) (+4000 exp)

elseif **You turn in:** [Voucher of Service to Naythox](/item/12499), [Swiftmoon's Head](/item/12498), [Receipt for Provisions Crate](/item/19029), [Disciple Symbol of Innoruuk](/item/1370)


>**Ithvol K-Jasn says:** Your devotion to the ideals of hatred and your service to our King Naythox Thex has proven your usefulness within these spires and within our great city. I award you the Regent Symbol of Innoruuk. Congratulations, Regent Soandso!


* __Faction:__ [Priests of Innoruuk](/faction/340) (50)


* __Faction:__ [King Naythox Thex](/faction/278) (7)


* __Faction:__ [Clerics of Tunare](/faction/226) (-17)


* __Faction:__ [Priests of Life](/faction/341) (-12)


* __Faction:__ [Priests of Marr](/faction/362) (-7)


* __Faction:__ [Primordial Malice](/faction/1522) (-200)


 **You receive:**  [Regent Symbol of Innoruuk](/item/1371) (+8000 exp)

**This NPC *should* return incorrect items given.**






