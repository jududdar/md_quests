# Bruax Grengar
## Dialog

if(eq.get_current_expansion() >= 4.0) then


**You say:** `hail`




>**Bruax Grengar says:** Hail Soandso. I am Bruax Grengar, master necromancer of the Bloodsabers. I assist not only young necromancers with their training but also aid all those Bloodsabers who have chosen to practice the [sorcerous arts]. If you a practitioner of a sorcerous art I can give you instructions to obtain an [outfit and robe] that will assist you in your work. Once you have been properly outfitted I will also assist you in acquiring a [Staff of the Bloodsabers].


**You say:** `sorcerous arts`




>**Bruax Grengar says:** I speak of those who practice the sorcerous arts other than necromancy: the arts of Enchantment, Magery, and Wizardry. It is a common misnomer proclaimed by those uneducated to the ways of the Plague Bringer that only Shadowknights and Necromancers serve Bertoxxulous. In fact this temple alone has members from all walks of life, from tailors, scholars, and blacksmiths to warriors and sorcerers.


**You say:** `outfit and robe`




>**Bruax Grengar says:** I have prepared this special curing kit for the crafting of an outfit and robe. The materials required for each article of clothing vary. Do you desire to craft a [scourge sorcerer cap], [scourge sorcerer wristband], [scourge sorcerer gloves], [scourge sorcerer boots], [scourge sorcerer sleeves], [scourge sorcerer pantaloons], or [scourge sorcerer robe]?



**You receive:**  [Curing Kit](/item/17125)


**You say:** `cap`




>**Bruax Grengar says:** To craft a Scourge Sorcerer Cap you will require two [silk thread], klicnik drone bile, and a large king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Cap Pattern.



**You receive:**  [Tattered Cap Pattern](/item/19555)


**You say:** `wristband`




>**Bruax Grengar says:** To craft a Scourge Sorcerer Wristband you require a [silk thread], klicnik drone bile, and a king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Wristband Pattern.



**You receive:**  [Tattered Wristband Pattern](/item/19558)


**You say:** `glove`




>**Bruax Grengar says:** To craft Scourge Sorcerer Gloves you require two [silk thread], klicnik drone bile, two giant field rat whiskers, and a large king snake skin. Once you have the necessary components combine them in your Curing Kit with this Tattered Glove Pattern.



**You receive:**  [Tattered Glove Pattern](/item/19559)


**You say:** `boot`




>**Bruax Grengar says:** To craft Scourge Sorcerer Boots you require two [silk thread], klicnik drone bile, and two large king snake skins. Once you have the necessary components combine them in your Curing Kit with this Tattered Boot Pattern.



**You receive:**  [Tattered Boot Pattern](/item/19561)


**You say:** `sleeve`




>**Bruax Grengar says:** To craft Scourge Sorcerer Sleeves you require two [silk thread], klicnik warrior bile, and two large king snake skins. Once you have the necessary components combine them in your Curing Kit with this Tattered Sleeves Pattern.



**You receive:**  [Tattered Sleeve Pattern](/item/19557)


**You say:** `pantaloon`




>**Bruax Grengar says:** To craft Scourge Sorcerer Pantaloons you require two [silk thread], klicnik warrior bile, and four large king snake skins. Once you have the necessary components combine them in your Curing Kit with this Tattered Leggings Pattern.



**You receive:**  [Tattered Pant Pattern](/item/19560)


**You say:** `robe`




>**Bruax Grengar says:** To craft a Scourge Sorcerer Robe you will require three [silk thread], klicnik noble bile, two giant king snake skins, and a giant whiskered bat fur. Once you have the necessary components combine them in your Curing Kit with this Tattered Robe Pattern.



**You receive:**  [Tattered Robe Pattern](/item/11395)


**You say:** `staff of the bloodsabers`




>**Bruax Grengar says:** A Staff of the Bloodsabers is a useful implement for young sorcerers dedicated to Bertoxxulous the Plague Lord. I will assist you in the creation of a staff but first you must complete a task for me. The sorcerers of The Order of Three are supporters of Antonius Bayle IV, the haughty ruler of Qeynos. They lend magical aid to the Knights of Thunder and Priests of Life to identify and capture members of the Bloodsabers. A rather troublesome member of The Order of Three, Larkin Tolman, has recently been spotted at a settlement in the Western Plains of Karana. Find this Larkin Tolman and bring me his head.

end

## Turn-Ins



local expansion_flag = eq.get_current_expansion();

if(expansion_flag >= 4.0 and  **You turn in:** [Larkin Tolman's Head](/item/20204)) then


>**Bruax Grengar says:** Well done. The Bloodsabers have many enemies within the city of Qeynos and its surrounding regions. You must exercise much caution when not within the safety of our temple here in the Qeynos Catacombs. Take this Rough Bloodsaber Staff and when you have gathered a Giant King Snake Skin, two Gnoll Fangs, and a Giant Fire Beetle Eye, return them to me with this staff and I will complete its construction.


* __Faction:__ [Bloodsabers](/faction/221) (10)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)


* __Faction:__ [Priests of Life](/faction/341) (-2)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:**  [Rough Bloodsaber Staff](/item/20203) (+500 exp)

elseif(expansion_flag >= 4.0 and  **You turn in:** [Gnoll Fang](/item/13915), [Rough Bloodsaber Staff](/item/20203), [Giant King Snake Skin](/item/19946), [Giant Fire Beetle Eye](/item/13251)) then


>*Bruax Grengar smooths the shaft of the staff, fashions a grip from the giant king snake skin, secures the giant fire beetle eye in a metal fixture and attaches it to the top of the staff. 'Here is your Staff of the Bloodsabers young Scourge Sorcerer. Go now and spread the disease!*


* __Faction:__ [Bloodsabers](/faction/221) (5)


* __Faction:__ [Guards of Qeynos](/faction/262) (-1)


* __Faction:__ [Opal Darkbriar](/faction/296) (1)


* __Faction:__ [Priests of Life](/faction/341) (-1)


* __Faction:__ [Corrupt Qeynos Guards](/faction/230) (1)


 **You receive:**  [Staff of the Bloodsabers](/item/20264) (+500 exp)

**This NPC *should* return incorrect items given.**






