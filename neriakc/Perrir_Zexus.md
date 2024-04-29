# Perrir Zexus
## Dialog

**You say:** `hail`



if **Faction** >= Amiable then



>**Perrir Zexus says:** Salutations, Soandso! Your devotion to our Lord Innoruuk is evident in your actions and on your soul. As a member of the Spires of Innoruuk, you are required to obtain and wear the symbol of your station among the clergy. I can award you the [hematite symbol of Innoruuk] worn by the initiates of the Spires.


elseif **Faction** >= Indifferent then



>**Perrir Zexus says:** Although I sense the hate building within you, you have not yet done enough service to this temple to be trusted!


else



>**Perrir Zexus says:** You are worthless and pathetic! You could never be of service to our temple!  Begone before your innards decorate our walls!




**You say:** `hematite symbol of Innoruuk`



if **Faction** >= Amiable +50 then



>**Perrir Zexus says:** The forest beyond the gates of our grand city has been shaped by the magic of our Lord Innoruuk to be more hospitable to our kind. There are halfling druids in the service of Karana who have set up shrines there in hopes of restoring the forest to its former state. They could never succeed in their task with their feeble powers granted by their insignificant god, yet still, they are a nuisance. Bring me four of the holy symbols worn by the druids and I shall grant you the initiate symbol of Innoruuk.


elseif **Faction** >= Indifferent then



>**Perrir Zexus says:** Although I sense the hate building within you, you have not yet done enough service to this temple to be trusted!


else



>**Perrir Zexus says:** You are worthless and pathetic! You could never be of service to our temple!  Begone before your innards decorate our walls!





## Turn-Ins



if **Faction** >= Amiable +50 and  **You turn in:** [Woven Grass Amulet](/item/14550), [Woven Grass Amulet](/item/14550), [Woven Grass Amulet](/item/14550), [Woven Grass Amulet](/item/14550)) then


>**Perrir Zexus says:** You have done well, young initiate. I grant you this medallion invested with the divine hatred of Innoruuk. Wear it proudly as a representation of your importance to these sacred spires. Now, if you will excuse me, I must proceed with the burning of these pathetic halfling symbols of faith.


* __Faction:__ [Priests of Innoruuk](/faction/340) (50)


* __Faction:__ [King Naythox Thex](/faction/278) (7)


* __Faction:__ [Priests of Marr](/faction/362) (-17)


* __Faction:__ [Clerics of Tunare](/faction/226) (-12)


* __Faction:__ [Priests of Life](/faction/341) (-7)


* __Faction:__ [Primordial Malice](/faction/1522) (-200)


 **You receive:**  [Initiate Symbol of Innoruuk](/item/1369) (+2000 exp)

elseif( **You turn in:** [A tattered note](/item/18756)) then 


>**Perrir Zexus says:** Welcome, child of Hate. I am Perrir Zexus, High Priest. We all draw power from the very source that created us, the will of Innoruuk. Here, put on this tunic. It is the tunic of our guild. Represent us well.


* __Faction:__ [Priests of Innoruuk](/faction/340) (100)


* __Faction:__ [King Naythox Thex](/faction/278) (15)


* __Faction:__ [Priests of Marr](/faction/362) (-35)


* __Faction:__ [Clerics of Tunare](/faction/226) (-25)


* __Faction:__ [Priests of Life](/faction/341) (-15)


* __Faction:__ [Primordial Malice](/faction/1522) (-400)


 **You receive:**  [Crimson Training Tunic*](/item/13585) (+20 exp)

elseif( **You turn in:** [note of recommendation](/item/18148)) then 


>**Perrir Zexus says:** Soandso, eh? My sister has a keen perception for seeing into a person's soul. You may store an abundance of hate but hate can be devoted to different ideals. Prove to me your devotion to our Lord Innoruuk by bringing me the skullcap of a Leatherfoot Raider who has invaded our forest. Go, Soandso, and do as I have requested.


* __Faction:__ [Priests of Innoruuk](/faction/340) (200)


* __Faction:__ [King Naythox Thex](/faction/278) (30)


* __Faction:__ [Priests of Marr](/faction/362) (-70)


* __Faction:__ [Clerics of Tunare](/faction/226) (-50)


* __Faction:__ [Priests of Life](/faction/341) (-30)


* __Faction:__ [Primordial Malice](/faction/1522) (-800)


 **You receive:** 0 (+750 exp)

elseif( **You turn in:** [Leatherfoot Raider Skullcap](/item/13113)) then 


>**Perrir Zexus says:** Fine work, Soandso! You are well on your way to reaping the rewards of the Spires of Innoruuk.


* __Faction:__ [Priests of Innoruuk](/faction/340) (10)


* __Faction:__ [King Naythox Thex](/faction/278) (1)


* __Faction:__ [Priests of Marr](/faction/362) (-3)


* __Faction:__ [Clerics of Tunare](/faction/226) (-2)


* __Faction:__ [Priests of Life](/faction/341) (-1)


* __Faction:__ [Primordial Malice](/faction/1522) (-40)


 **You receive:** 0 (+250 exp)

**This NPC *should* return incorrect items given.**






