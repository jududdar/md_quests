# War Baron Eator
## Dialog

**You say:** `Hail`



>*War Baron Eator turns to you and snorts in anger. Some mucus lands on your cheek. 'Troopers! I thought I ordered you to keep all new recruits away from this chamber! Go, child. The War Baron of Cabilis has no time for games. See this intruder out!!'*

**You say:** `memory`



if **Faction** >= Amiable then



>*War Baron Eator takes a step back and thinks to himself. Phlegm dribbles off his lips. 'The Memory of Sebilis. Kept within my personal chambers. They have been taken. Taken by some croakin' Forsaken no doubt!! You have been sent to me because you show excellent prowess. Find my Memory and bring it to me with your footman's pike.'*


elseif **Faction** >= Indifferent then



>**War Baron Eator says:** No Iksar resident will have anything to do with you!


else



>**War Baron Eator says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.


**You say:** `trooper`



if **Faction** >= Amiable then



>**War Baron Eator says:** So you are a trooper? Word of your deeds has been spreading through the legion. If you truly wield the pike of a trooper, then go and serve the garrisons of swamp, lake and woods. Report to the Warlord and tell him you are a [trooper reporting for duty]. Their recommendations and your trooper pike shall earn you the rank of legionnaire.


elseif **Faction** >= Indifferent then



>**War Baron Eator says:** No Iksar resident will have anything to do with you!


else



>**War Baron Eator says:** Hiss!  Fool!  Fear the Legion of Cabilis for you are no ally to us.  Leave while you can.

end

## Turn-Ins



local text1 = "I await three letters of recommendation and your trooper pike.";


local text2 = "shines a bright smile which quickly fades to a frown. 'The memory is not complete. ..sniff, sniff.. A reward for my memory and your footman's pike.";




if **You turn in:** [Dark Grey Tome](/item/18464), [Sarnak Hide](/item/22919)


>*War Baron Eator smiles at your dedication to Cazic Thule and hands you a small gem.*


* __Faction:__ [Swift Tails](/faction/444) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:**  [Mark of Clarity](/item/7881) (+20000 exp)

elseif **You turn in:** [Light Black Tome](/item/18463), [Chokadai Scale](/item/22918)


>*War Baron Eator smiles at your dedication to Cazic Thule and hands you a small gem.*


* __Faction:__ [Swift Tails](/faction/444) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (1)


 **You receive:**  [Mark of Clarity](/item/7881) (+20000 exp)

elseif **Faction** >= Amiable and  **You turn in:** [An Emerald](/item/12899), [A Sapphire](/item/12898), [A Ruby](/item/12896), [Footman's Pike](/item/5132)


>*War Baron Eator gulps down a wad of phlegm. 'My memory has returned! Soandso! You are no footman. I grant you the rank of soldier. Go and forge your weapon. Do not return to me until you become a [brave trooper of the empire].'*


* __Faction:__ [Cabilis Residents](/faction/440) (20)


* __Faction:__ [Legion of Cabilis](/faction/441) (5)


* __Faction:__ [Scaled Mystics](/faction/445) (5)


* __Faction:__ [Swift Tails](/faction/444) (5)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (5)


 **You receive:**  [Soldier Head Plans](/item/12476) (+800 exp)

elseif **Faction** >= Amiable and  **You turn in:** [Legionnaire Recommendation](/item/18073), [Legionnaire Recommendation](/item/18072), [Legionnaire Recommendation](/item/18074), [Trooper's Pike](/item/5134)


>*War Baron Eator takes away your pike and hands you plans not for a pike head, but for the crown of another polearm. 'It is time to wield the weapon of a [true warrior of the legion]. You have done well, Legionnaire Soandso!'*


* __Faction:__ [Cabilis Residents](/faction/440) (2)


* __Faction:__ [Legion of Cabilis](/faction/441) (2)


* __Faction:__ [Scaled Mystics](/faction/445) (2)


* __Faction:__ [Swift Tails](/faction/444) (2)


* __Faction:__ [Crusaders of Greenmist](/faction/442) (2)


 **You receive:**  [Legionnaire Crown Plans](/item/12478) (+4000 exp)

**This NPC *should* return incorrect items given.**





